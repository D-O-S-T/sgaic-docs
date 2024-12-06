# Github

Aqui estão algumas diretrizes para garantirmos um trabalho organizado e eficiente no nosso repositório.

## Merges

Para que ocorram merges, é necessário criar pull requests que devem ser aprovados por um número mínimo de **três** (3) pessoas, uma delas deve incluir o líder do projeto.

## Estrutura do projeto

O repositório está dividido nas pastas:  
- `backend`: código do backend.  
- `frontend`: código do frontend.

## Branches
Cada um deve criar e trabalhar em branches específicas de acordo com sua área de atuação.  
Isso facilita o controle de versões e a revisão do código.

### Branch `main`

- A branch `main` não está protegida para lidar com possíveis imprevistos, mas:  
- Evite fazer commits ou merges diretamente na main. 
- É importante seguir o fluxo correto para que o repositório se mantenha íntegro.

### Nomenclatura das branches

Use nomes descritivos e com sentido para as branches. Aqui está o modelo a ser seguido:

- **`feature/nome-da-feature`**: Para implementar novos recursos.  
  Exemplo: `feature/implementacao-logica-auth`

- **`refactor/nome-do-refactor`**: Para refatorações (métodos, endpoints, models, etc).  
  Exemplo: `refactor/endpoints-usercontroller`

- **`bugfix/nome-do-bugfix`**: Para corrigir erros e bugs.  
  Exemplo: `bugfix/erro-de-versionamento`

## Commits

Escolha nomes significativos para os commits, que expliquem claramente o que foi feito.
