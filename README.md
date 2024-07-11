# ServeTest-Postman

Este repositório contém testes automatizados para a API ServeRest, utilizando Postman para a execução dos testes e coleção de resultados. O projeto ServeTest abrange os módulos de Usuários, Login, Produtos e Carrinho.

## Objetivo

O objetivo deste projeto é garantir que todos os endpoints da API ServeRest funcionem conforme esperado, realizando operações CRUD e validações diversas para Usuários, Login, Produtos e Carrinho.

## Ferramentas Utilizadas

- **Postman**: Ferramenta de teste de API para desenvolvimento, teste e documentação de APIs.
- **Newman**: CLI do Postman para a execução de coleções de teste de API.
- **ServeRest API**: API utilizada para a realização dos testes.

## Swagger 
#### [Swagger do projeto](https://serverest.dev/#)

  ![Swagger ServeRest](https://github.com/carolprotasio/ServeTest-Postman/blob/main/swagger.png)

## Estrutura do Projeto

### 1. API Usuários

- **CRUD API Usuários**
  - **POST /Criar Usuário**: Criação de um novo usuário.
  - **PUT /Atualizar Usuário**: Atualização de um usuário existente.
  - **GET /Buscar Usuário por ID**: Busca de um usuário específico.
  - **DELETE /Deletar Usuário**: Exclusão de um usuário.
 
  - ![Testes_usuarios](https://github.com/carolprotasio/ServeTest-Postman/blob/main/usuario_collection.png)

### 2. API Login

- **Autenticação**
  - **POST /Criar Usuário**: Criação de um novo usuário.
  - **POST /Realizar Login com Sucesso**: Autenticação de um usuário válido.
  - **DELETE /Deletar Usuário**: Exclusão de um usuário.
  - **POST /Validação Login Excluído**: Validação de login com usuário excluído.
 
     ![Testes_login](https://github.com/carolprotasio/ServeTest-Postman/blob/main/login_collection.png)

### 3. API Produto

- **CRUD API Produtos**
  - **POST /Criar Usuário**: Criação de um novo usuário.
  - **POST /Realizar Login com Sucesso**: Autenticação de um usuário válido.
  - **POST /Criar Produto**: Criação de um novo produto.
  - **GET /Buscar Produto por ID**: Busca de um produto específico.
  - **PUT /Atualizar Produto**: Atualização de um produto existente.
  - **GET /Checar Produto Alterado**: Busca o produto específico que foi alterado.
  - **DELETE /Deletar Produto**: Exclusão de um produto especifico.
 
     ![Testes_produtos](https://github.com/carolprotasio/ServeTest-Postman/blob/main/produto_collection.png)

### 4. API Carrinhos

- **Realizar Compra**
  - **POST /Criar Usuário**: Criação de um novo usuário.
  - **POST /Realizar Login com Sucesso**: Autenticação de um usuário válido.
  - **POST /Criar Produto 1**: Criação de um novo produto (produto 1).
  - **POST /Criar Produto 2**: Criação de um novo produto (produto 2).
  - **POST /Cadastrar novo carrinho**: Criação de carrrinho com os produtos cadastrados.
  - **GET /Buscar carrinho por ID**: Busca de um carrinho específico.
  - **DELETE /Realizar Compra**: Realização de uma compra com produtos.
  - **DELETE /Cancelar Compra**: Cancelamento de uma compra.
 
     ![Testes_carrinho](https://github.com/carolprotasio/ServeTest-Postman/blob/main/carrinho_collection.png)

### 5. Listar

- **LISTAR**
  - **GET /Buscar Produtos**: Listagem de produtos.
  - **GET /Buscar Usuários**: Listagem de usuários.
  - **GET /Buscar Carrinhos**: Listagem de carrinhos.
 
     ![Testes_listar](https://github.com/carolprotasio/ServeTest-Postman/blob/main/listar_collection.png)


