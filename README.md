# CRUD em Node.js

Este repositório contém um exemplo simples de como criar um CRUD (Create, Read, Update, Delete) em Node.js, utilizando o PostgreSQL como banco de dados.

## Pré-requisitos

Antes de começar, certifique-se de ter o Node.js e o PostgreSQL instalados em sua máquina.

## Configuração

1. Clone este repositório em sua máquina local.

2. Instale as dependências do projeto utilizando o seguinte comando:

```bash
npm install
```

3. Configure as variáveis de ambiente no arquivo `.env` com as informações do seu banco de dados PostgreSQL:

```
PGHOST=seu_host_do_postgres
PGDATABASE=seu_banco_de_dados
PGUSER=seu_usuario_do_postgres
PGPASSWORD=sua_senha_do_postgres
```

## Funcionalidades

- **Create**: Adiciona um novo item ao banco de dados.
- **Read**: Recupera informações do banco de dados.
- **Update**: Atualiza um item existente no banco de dados.
- **Delete**: Remove um item do banco de dados.

## Executando o Projeto

Para executar o projeto, utilize o seguinte comando:

```bash
npm start
```

Isso iniciará o servidor Node.js. Você pode acessar as rotas CRUD utilizando um cliente HTTP, como o Postman ou o cURL.

## Deploy
https://nodejs-crud-axfj.onrender.com

## Contribuindo

Sinta-se à vontade para contribuir com melhorias neste projeto! Basta criar um pull request e ficaremos felizes em revisá-lo.
