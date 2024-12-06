# Front-End

- **Framework:** Angular 17.3.9  
- **Linguagem:** TypeScript, JavaScript, HTML  
- **Estilo:** SCSS (SASS)  
- **Design:** Protótipos criados no Figma com base em princípios de responsividade e acessibilidade.  

# Estrutura do Front-End

- **Arquitetura de Componentes:** A aplicação é modularizada em componentes reutilizáveis para garantir organização e manutenção fácil.  
- **Navegação:** Rotas gerenciadas com o módulo de roteamento do Angular para navegação entre as páginas.  
- **Responsividade:** Layout desenvolvido para se ajustar automaticamente a diferentes tamanhos de tela, garantindo boa experiência em dispositivos móveis e desktops.  

# IDE Recomendada

- **IDE:** Visual Studio Code  
- **Extensões Sugeridas:** Angular Language Service, Prettier, e SCSS IntelliSense para produtividade.  

# Estilo e Temas

- **Paleta de Cores:** A paleta segue um tema escuro com cores complementares, alinhada ao design no Figma.  
- **Tipografia:** Uso de fontes legíveis e consistentes para uma interface clara e intuitiva.  

# Integração com Back-End

- **Comunicação:** Chamadas à API realizadas com HttpClient para consumir endpoints REST.  
- **Validação de Dados:** Validações implementadas no front-end antes de enviar dados ao back-end.

# Como Iniciar e Rodar um Projeto Angular

Ao trabalhar com o *Angular*, o primeiro passo para explorar a criação de páginas e funcionalidades é aprender como rodar o projeto localmente. O Angular oferece ferramentas poderosas para desenvolvimento, incluindo seu próprio servidor de desenvolvimento. Aqui está um guia introdutório para começar:

# Pré-requisitos

Antes de tudo, certifique-se de ter o *Node.js* instalado no seu computador. Ele é necessário para gerenciar pacotes e executar projetos Angular. Você pode verificar se ele está instalado executando o comando:

bash
node -v
npm -v


Se ainda não estiver instalado, faça o download no site oficial do Node.js: [https://nodejs.org](https://nodejs.org).

Além disso, é preciso instalar o *Angular CLI* (Command Line Interface), a ferramenta que facilita a criação e gerenciamento de projetos Angular. Para isso, execute:

bash
npm install -g @angular/cli


Após a instalação, confirme a versão instalada:

bash
ng version


# Iniciando um Novo Projeto Angular

Com o Angular CLI configurado, você pode criar um novo projeto executando:

bash
ng new nome-do-projeto


- **Durante a criação**, será solicitado que você escolha configurações como suporte ao TypeScript e inclusão de ferramentas de testes. Use as opções padrão ou personalize conforme necessário.
- **Navegue até a pasta do projeto**:

bash
cd nome-do-projeto


# Rodando o Servidor de Desenvolvimento

Para visualizar e testar o projeto em um navegador, use o servidor de desenvolvimento integrado. Basta executar:

bash
ng serve --open


- O comando --open abre automaticamente o navegador padrão no endereço http://localhost:4200.
- Caso prefira rodar o projeto em uma porta específica, você pode usar:

bash
ng serve --port 4300


# Estrutura do Projeto Angular

Ao abrir o projeto no seu editor de código, como o *Visual Studio Code*, você verá uma estrutura de pastas organizada:

- **src/app**: Contém os componentes, serviços e arquivos principais do seu aplicativo.
- **src/assets**: Armazena recursos como imagens e arquivos estáticos.
- **src/environments**: Configurações específicas para diferentes ambientes (desenvolvimento ou produção).

# Dicas para Começar

1. **Criação de Componentes**: Use o Angular CLI para criar novos componentes. Por exemplo:

   bash
   ng generate component nome-do-componente
   

   Isso cria automaticamente os arquivos HTML, CSS e TypeScript necessários.

2. **Atualização de Dependências**: Sempre mantenha as dependências do projeto atualizadas para garantir compatibilidade e acesso aos últimos recursos. Execute:

   bash
   npm update
   

3. **Hot Reload**: Enquanto o servidor de desenvolvimento está ativo, qualquer alteração no código é automaticamente refletida no navegador, economizando tempo durante o desenvolvimento.