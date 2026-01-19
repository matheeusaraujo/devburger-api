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
## 📸 Preview da Aplicação

### 🏠 Home / Menu
<img src=".github/screenshots/home.png" alt="Home DevBurger" width="800"/>

---

### 🛒 Carrinho de Compras
<img src=".github/screenshots/cart.png" alt="Carrinho DevBurger" width="800"/>

---

### 🔐 Login
<img src=".github/screenshots/login.png" alt="Login DevBurger" width="800"/>

---

### 💳 Checkout
<img src=".github/screenshots/checkout.png" alt="Checkout DevBurger" width="800"/>

---

### 🛠️ Painel Admin
<img src=".github/screenshots/admin-products.png" alt="Admin DevBurger" width="800"/>

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
git clone https://github.com/matheeusaraujo/devburger-interface.git
````
## Acessar a pasta
```bash
cd devburger-interface
````
## Instalar as dependências
```bash
yarn install
````
## ▶️ Executando a Aplicação
📍 A aplicação será aberta geralmente em: http://localhost:5173
```bash
yarn dev
````

##  Licença
<p>
  Este projeto está sob a licença MIT.
</p>










