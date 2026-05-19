# 🛒 E-commerce API – Flask

Uma API REST simples de e-commerce desenvolvida com **Python e Flask**, com foco em práticas de back-end como autenticação, manipulação de banco de dados e construção de APIs.

---

## 📌 Sobre o projeto

Este projeto simula um sistema básico de e-commerce, permitindo o gerenciamento de usuários, produtos e carrinho de compras.

Foi desenvolvido com o objetivo de praticar conceitos fundamentais de back-end, como:

- CRUD completo
- Autenticação de usuários
- Criação de APIs RESTful
- Integração com banco de dados relacional
- Relacionamentos entre tabelas com SQLAlchemy

---

## 🚀 Funcionalidades

### 👤 Usuários
- Login e logout de usuários

### 📦 Produtos
- Cadastro de produtos
- Listagem de produtos
- Busca de produto por ID
- Atualização de produtos
- Remoção de produtos

### 🛒 Carrinho de compras
- Adicionar itens ao carrinho
- Remover itens do carrinho
- Visualizar carrinho
- Realizar checkout (limpa o carrinho)

---

## 🧰 Tecnologias utilizadas

- Python 3
- Flask
- Flask-SQLAlchemy
- Flask-Login
- Flask-CORS
- SQLite

---

## 📂 Estrutura do projeto

```bash
.
├── app/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── extensions.py
│   └── __init__.py
├── migrations/
├── config.py
├── run.py
└── requirements.txt

# Clone o repositório
git clone https://github.com/seu-usuario/seu-repo.git

# Entre na pasta
cd seu-repo

# Crie um ambiente virtual
python -m venv venv

# Ative o ambiente
# Windows:
venv\Scripts\activate
# Linux/Mac:
source venv/bin/activate

# Instale as dependências
pip install -r requirements.txt

# Execute a aplicação
python run.py
