# ProjetoEstudoDB

Projeto para gerenciar cadastros de clientes utilizando **MongoDB** e **Node.js**.

## Objetivo

Projeto de banco de dados com Mongodb e node.js com a finalidade de adicionar, atualizar, e excluir cadastros de "clientes". 

## Pré-requisitos

- [Node.js](https://nodejs.org/) (versão 14.x ou superior)
- [MongoDB](https://www.mongodb.com/) em execução (localmente ou via Atlas)
- URI de conexão configurada em `database.js`

## Como usar

1. Clone o repositório:
    ```bash
    git clone https://github.com/LuizDamasAmorim/ProjetoEstudoDB.git
    ```

2. Entre na pasta do projeto:
    ```bash
    cd ProjetoEstudoDB
    ```

3. Instale as dependências:
    ```bash
    npm install
    ```

4. Configure a URI do MongoDB:
    ```js
    const url = 'mongodb+srv://usuario:senha@cluster.mongodb.net/nomeDoBanco'
    ```

5. Execute o projeto:
    ```bash
    node main.js
    ```

## Funcionalidades

- **Create**: Adicionar novos clientes.
- **Update**: Atualizar dados de clientes existentes.
- **Delete**: Excluir clientes do banco de dados.

