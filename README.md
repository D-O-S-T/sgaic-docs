# Documentação SGA-IC

SGA-IC é um sistema desenvolvido para auxiliar na gestão de pesquisas científicas dentro de um ambiente acadêmico, facilitando o controle e o gerenciamento de informações relacionadas a projetos de iniciação científica.

O sistema facilita tarefas comuns de gerenciamento em ambientes acadêmicos, como registro de alunos, gestão de projetos, atividades, relatórios e muito mais.

Nessa wiki você encontra documentação relevantes quanto ao [Back End](backend.md), [Front End](frontend.md) e [Banco de Dados](db.md) do projeto. Navegue na sidebar ao lado para encontrar o que deseja.

## Suporte
SGA-IC está em fase de **prototipagem** e é desenvolvido por alunos universitários, que atualmente desempenham todas as funções. No entanto, existem planos para o futuro, incluindo a formalização da nossa organização, [D-O-S-T](https://github.com/D-O-S-T), o que possibilitaria a expansão do escopo do sistema, dependendo de investimentos externos e bolsas. Além disso, estamos avaliando a integração do projeto a um servidor local da universidade para uma possível implantação.

Se você deseja relatar um bug ou sugerir uma funcionalidade, utilize a página de [Issues](https://github.com/D-O-S-T/sgaic/issues) do próprio repositório. Tentamos manter o SGA-IC atualizado e em constante manutenção.

## License
SGA-IC está licenciado sob a [Licença MIT](https://github.com/D-O-S-T/sgaic/blob/main/LICENSE.txt).

## Documentação (Setup)
Para essa documentação, usamos o [Docsify](https://github.com/docsifyjs/docsify).

Primeiro, é necessário ter a ferramenta (Docsify) instalada. É recomendado instalar o `docsify-cli` globalmente, pois ele ajuda a inicializar e visualizar o site localmente.

```bash
npm i docsify-cli -g
```

- `index.html`: arquivo base do site
- `README.md`: arquivo markdown renderizado como a página inicial
- `.nojekyll`: evita que o GitHub Pages ignore arquivos que começam com um sublinhado `_`

Você pode facilmente atualizar a documentação em ./docs/README.md e, claro, pode adicionar mais páginas.

## Preview do site
Abra a pasta do projeto SGA-IC no seu computador, verifique se você está na branch `docs` e inicie o servidor local executando o seguinte comando:

```bash
docsify serve docs
```

Você poderá visualizar seu site no navegador em http://localhost:3000.

---
Para mais exemplos de uso do `docsify-cli`, visite a [wiki](https://docsify.js.org/) do Docsify.

Mais temas pro Docsify: https://github.com/jhildenbiddle/docsify-themeable