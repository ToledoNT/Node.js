# API de Filmes

Este projeto consiste em uma API RESTful desenvolvida em Node.js com Express.js e MongoDB utilizando o Mongoose. A API permite o gerenciamento de informações sobre filmes, oferecendo funcionalidades básicas de criação, leitura, atualização e exclusão (CRUD) de registros de filmes.

## Como Utilizar

### Pré-requisitos

- Node.js instalado
- MongoDB instalado e em execução
- Conexão com a internet (para instalação de dependências)

### Instalação

1. Clone o repositório para o seu computador.
2. No terminal, navegue até o diretório do projeto.
3. Execute o comando `npm install` para instalar as dependências.

### Configuração do Banco de Dados

1. Abra o arquivo `index.js`.
2. Substitua `'URL_DO_SEU_BANCO_DE_DADOS'` pela URL do seu banco de dados MongoDB.

### Execução

1. No terminal, dentro do diretório do projeto, execute o comando `node app.js` ou `npm start` para iniciar o servidor.
2. O servidor estará acessível em `http://localhost:3000`.

### Endpoints da API

- **GET '/':** Retorna todos os filmes presentes no banco de dados.
- **DELETE '/:id':** Exclui um filme com o ID fornecido.
- **PUT '/:id':** Atualiza os detalhes de um filme com o ID fornecido.
- **POST '/':** Cria um novo filme com os dados fornecidos.

Certifique-se de fornecer os dados corretos conforme esperado pelo formato do JSON para cada endpoint.


