<h1 align="center">🍔 DevBurger API</h1>

<p align="center">
  API RESTful para gerenciamento de uma hamburgueria virtual, desenvolvida com Node.js e Express.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/node-%3E%3D18.0.0-brightgreen" />
  <img src="https://img.shields.io/badge/express-4.x-blue" />
  <img src="https://img.shields.io/badge/license-MIT-green" />
  <img src="https://img.shields.io/badge/status em-%20Concluido-green" />
</p>

---

##  Sobre o Projeto

O **DevBurger API** é o backend de uma aplicação de hamburgueria, responsável pelo gerenciamento de usuários, produtos, categorias e pedidos.

Este projeto foi desenvolvido com foco em:
- Boas práticas de **APIs REST**
- Organização de código
- Segurança
- Autenticação e autorização
- Integração com banco de dados

Ideal para estudos e demonstração de conhecimentos em **backend com Node.js**.

---

## Funcionalidades

- 👤 Cadastro e autenticação de usuários
- 🔐 Autenticação via JWT
- 🔑 Criptografia de senhas com Bcrypt
- 📁 CRUD de categorias
- 🍔 CRUD de produtos
- 📦 Criação e listagem de pedidos
- 🖼️ Upload de imagens
- 🛡️ Rotas protegidas por middleware

---

##  Tecnologias Utilizadas

- **Node.js**
- **Express.js**
- **JavaScript**
- **Sequelize (ORM)**
- **Banco de Dados SQL**
- **JWT (JSON Web Token)**
- **Bcrypt**
- **Multer**
- **Dotenv**

---

##  Estrutura do Projeto

```bash
devburger-api
├── src
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middlewares
│   ├── config
│   └── database
├── .env.example
├── .sequelizerc
├── package.json
└── README.md
````
## Como Executar o Projeto
```bash
git clone https://github.com/matheeusaraujo/devburger-api.git
````
## Acessar a pasta
```bash
cd devburger-api
````
## Instalar as dependências
```bash
yarn install
````
##  Variáveis de Ambiente
📍 Crie um arquivo .env baseado no .env.example:
```bash
PORT=3000

DB_HOST=localhost
DB_USER=seu_usuario
DB_PASS=sua_senha
DB_NAME=devburger

JWT_SECRET=sua_chave_secreta
````

## ▶️ Executando a Aplicação
📍 A API estará disponível em: http://localhost:3000
```bash
yarn dev
````

##  Endpoints Principais

| Método | Endpoint | Descrição |  
| :--- | :--- | :--- | 
| **`POST`** | `/users` | → Cadastro de usuário
| **`POST`** | `/session` | → Login
| **`GET`** | `/categories` | → Listar categorias
| **`POST`** | `categories` | → Criar categoria
| **`GET`** | `products` | → Listar produtos
| **`POST`** | `/products` | → Criar produto
| **`GET`** | `/orders` | → Listar pedidos
| **`POST`** | `/orders` | → Criar pedido

## Scripts Disponíveis

```bash
yarn dev       # Executa a aplicação em modo desenvolvimento
yarn start     # Executa a aplicação em modo produção
````
