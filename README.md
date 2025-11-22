✨ Sobre o projeto

Criei esse projeto para aprender mais sobre desenvolvimento Back-End, organização de código e como montar uma API do zero.
É simples, mas foi muito útil para praticar a criação de rotas, modelos e conexão com banco de dados.

🛍️ Product API (FastAPI + SQLite)

Este é um projeto simples que fiz para praticar Back-End com Python e FastAPI.
A ideia é ter uma API de produtos, onde dá para cadastrar, listar, editar e deletar informações.

🚀 Como rodar o projeto

Instale as dependências:
pip install -r requirements.txt
Crie o arquivo .env (pode copiar o .env.example):
cp .env.example .env
Inicie o servidor:
uvicorn app.main:app --reload
Acesse no navegador:
Swagger → http://127.0.0.1:8000/docs
Health Check → http://127.0.0.1:8000/health

📌 O que essa API faz

Cria produtos
Lista todos os produtos
Busca um produto pelo ID
Atualiza um produto
Deleta um produto
Simples e direto ao ponto.

📂 Estrutura do projeto (resumida)
app/
  api/
  services/
  repository/
  models.py
  schemas.py
  db.py
  main.py

Organizei em camadas para deixar mais parecido com projetos reais.

🛠 Tecnologias usadas

Python
FastAPI
SQLite
SQLAlchemy
