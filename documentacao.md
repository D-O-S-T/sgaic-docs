# Documentação
Esta documentação foi elaborada com a ferramenta [Docsify](https://github.com/docsifyjs/docsify).

## Setup
Para editar a documentação, é necessário instalar o `docsify-cli` globalmente, pois ele ajuda a inicializar e visualizar o site localmente.

```bash
npm i docsify-cli -g
```

- `index.html`: arquivo base do site
- `README.md`: arquivo markdown renderizado como a página inicial
- `.nojekyll`: evita que o GitHub Pages ignore arquivos que começam com um sublinhado `_`

Você pode facilmente atualizar a documentação em `./docs/README.md` e, claro, pode adicionar mais páginas.

## Preview do site
Abra a pasta do projeto SGA-IC no seu computador, verifique se você está na branch `docs` e inicie o servidor local executando o seguinte comando:

```bash
docsify serve docs
```

Você poderá visualizar seu site no navegador em http://localhost:3000.

---
Para mais exemplos de uso do `docsify-cli`, visite a [wiki](https://docsify.js.org/) do Docsify.

Mais temas pro Docsify: https://github.com/jhildenbiddle/docsify-themeable