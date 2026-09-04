# Aurora Odontologia — Landing Page (projeto de estudo)

**Ver online:** https://pedrobartkevihi.github.io/LandingPageDentista/

Landing page **fictícia** de uma clínica odontológica, criada **para fins de
estudo**. Partindo de um exercício de curso feito só com HTML e CSS, o objetivo
foi modernizar o visual — layout, tipografia, cores, espaçamentos, botões,
cards, responsividade e pequenas interações — mantendo o estilo de escrita do
código original.

A clínica **Aurora Odontologia**, a **Dra. Marina Rocha** e todos os dados de
contato, endereço e depoimentos são inventados para este projeto e não
correspondem a nenhuma pessoa ou empresa real.

## Tecnologias

- HTML5
- CSS3 (variáveis em `:root`, flexbox, grid, `clamp()` e media queries)
- JavaScript (vanilla, sem dependências)
- [Google Fonts](https://fonts.google.com/) — Montserrat (OFL)

Sem frameworks e sem etapa de build: é só abrir o `index.html`.

## Estrutura

```
Projeto3/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── imagens/
    ├── icone_dente.png     (ícone usado nos cards de serviços)
    ├── perfil-dentista.jpg (foto da seção "A clínica")
    ├── mosaico-1..6.jpg    (galeria da seção principal)
    └── social-1..6.jpg     (galeria da seção social)
```

Os ícones da logo, do Instagram e do Facebook são SVGs simples, desenhados
direto no `index.html` (sem depender de arquivo de imagem).

## Seções

1. **Header** — logo (ícone + marca textual) e menu (vira dropdown no mobile).
2. **Mosaico** — chamada principal (kicker, título e botão) e galeria de fotos.
3. **Serviços** — três cartões com o ícone do dente, sobre o mosaico.
4. **A clínica** — foto e apresentação da profissional.
5. **Vídeos** — três vídeos incorporados em 16:9.
6. **Tratamentos** — grade de cartões com os procedimentos.
7. **Depoimentos** — depoimentos de pacientes em cartões.
8. **Social** — faixas de Instagram e Facebook com galeria.
9. **Contato** — formulário (nome, e-mail, telefone e mensagem).
10. **Rodapé** — contato, horários e endereço.

## Interações (`js/script.js`)

- Abre/fecha o menu no mobile (com `Esc`, clique fora e clique em link).
- Sombra no header ao rolar a página.
- Elementos `[data-revelar]` surgem ao entrar na tela (`IntersectionObserver`).
- Feedback ao enviar o formulário (não há back-end).
- Respeita `prefers-reduced-motion` e funciona sem JavaScript.

## Como executar

Abra o `index.html` no navegador, ou rode um servidor estático na pasta do
projeto:

```bash
python -m http.server 8080
```

E acesse `http://localhost:8080`.

## Créditos das imagens

As fotos vêm do [Pexels](https://www.pexels.com/) (licença livre, sem
necessidade de atribuição) e foram apenas redimensionadas e otimizadas. O
ícone da logo é um desenho simples em SVG, feito para este projeto.

## Uso

Repositório de **estudo de front-end, sem fins comerciais**. O código-fonte
(HTML, CSS e JavaScript) é de autoria de **Pedro Farias** e pode ser
reaproveitado livremente. Toda a identidade (nome da clínica, profissional,
textos e contatos) é fictícia.
