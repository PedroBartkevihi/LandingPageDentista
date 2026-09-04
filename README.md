# Landing Page — Dra. Marina Rocha (projeto de estudo)

**Ver online:** https://pedrobartkevihi.github.io/LandingPageDentista/

Recriação **para fins de estudo** de uma landing page de consultório
odontológico. Partindo de um exercício de curso feito só com HTML e CSS, o
objetivo aqui foi modernizar o visual — layout, tipografia, cores,
espaçamentos, botões, cards, responsividade e pequenas interações — mantendo a
mesma ideia, o mesmo conteúdo e o estilo de escrita do código original.

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
    ├── logo.png
    ├── img_perfil.png
    ├── depoimento1.png
    ├── icone_dente.png
    ├── inst.png
    ├── fb.png
    └── menu-mobile.png   (hamburguer do original; hoje o botão é feito em CSS)
```

## Seções

1. **Header** — logo e menu (vira dropdown no mobile, pelo `.menu-mobile`).
2. **Mosaico** — chamada principal (kicker, título e botão) e galeria de fotos.
3. **Serviços** — três cartões com o ícone do dente, sobre o mosaico.
4. **Perfil** — foto e apresentação da profissional.
5. **Vídeos** — três vídeos incorporados em 16:9.
6. **Tratamentos** — grade de cartões com os procedimentos.
7. **Depoimentos** — depoimentos de pacientes em cartões.
8. **Social** — faixas de Instagram e Facebook com galeria.
9. **Contato** — formulário (nome, e-mail, telefone e mensagem).
10. **Rodapé** — telefone, horários e endereço.

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

## Uso educacional e direitos

Este repositório é **apenas um exercício de front-end, sem fins comerciais**.

- O nome, a logo e a foto que aparecem na página pertencem aos seus respectivos
  titulares e são usados aqui só a título ilustrativo, para estudo.
- Os textos de serviços, tratamentos e depoimentos são fictícios, escritos
  apenas para preencher o layout.
- O código-fonte (HTML, CSS e JavaScript) é de autoria de **Pedro Farias** e
  pode ser reaproveitado livremente.
- Para uso como portfólio público, o recomendado é **trocar a logo e as
  imagens** por material próprio ou de bancos livres (ex.: Unsplash, Pexels).
- Caso algum detentor de direitos entre em contato, o conteúdo será removido.
