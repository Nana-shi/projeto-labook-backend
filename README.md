# PROJETO LABOOK

## Introdução

O Projeto 'Labook' é a simulação de uma rede social utilizando os conhecimentos em criação de APIs e banco de dados junto com a implementação de segurança e codigos mais escaláveis.

As informações contidas no banco de dados são as seguintes:

 - Informações sobre os usuários cadastrados
 - Informações sobre as postagens cadastradas

 Para acessar a documentação da API, clique [aqui!](https://documenter.getpostman.com/view/24461172/2s93CHtZwd)

## Descrição

### Como instalar as dependencias do projeto
 - É necessario ter Node e NPM já instalados na sua maquina!
 - Para instalar as dependencias do projeto basta rodar em um terminal o seguinte comando: npm install.

 ### Executando o projeto
  - npm start: Estabelece a conexão com o banco de dados mas é necessario rodar o comando novamente a cada nova mundança no projeto.
  - npm run dev: Estabelece a conexão com o banco de dados e reinicia automaticamente o servidor localhost toda a vez que o projeto for alterado e salvo.

### EndPoints
 - Signup: Endpoint para cadastrar um usuário;
 - Login: Endpoint de login de um usuário cadastrado, retorna um token;
 - Get Posts: Endpoint para listagem de postagens criadas, é necessário o token de login;
 - Create Post: Endpoint de criação de uma postagem, é necessário o token de login;
 - Edit Post: Endpoint para edição de um post já existente, é necessario token de login do criador do post;
 - Delete Post: Endpoint para deletar um post já existente, é necessario token de login do criador do post ou de usuário Admin;
 - Like/Dislike Post: Endpoint para dar like ou dislike em um post existente;

 ### Conteúdos abordados na criação do projeto
    - NodeJS
    - Typescript
    - Express
    - SQL e SQLite
    - Knex
    - POO
    - Arquitetura em camadas
    - Geração de UUID
    - Geração de hashes
    - Autenticação e autorização
    - Roteamento
    - Postman

 ## Tecnologias

![NodeJs](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)


### Programas utilizados:
 - VSCode
 - Postman API Platform

 ## Contato

 G-mail: leof.pereira2@gmail.com