# 📚 API do Blog – Node.js, Express e SQLite

Este projeto é uma API RESTful para um sistema de blog com cadastro de usuários, autenticação JWT e postagem de mensagens.

# 🚀 Tecnologias
Node.js
Express.js
SQLite com Knex.js
JWT (Token Web JSON)
bcryptjs

# 📦 Como rodar o projeto
# Clone o repositório
git clone https://github.com/LuSouzaB/blog.git
cd blog-api

# Instale as dependências
npm install

## Crie o banco de dados e tabelas
npm run criar-db

## Inicie o servidor
npm start

Uma API estará disponível em: http://localhost:3000

#🔐 Rotas da API
POST /inscrição

Cadastrar um novo usuário

POST /inscrição
Cadastrar um novo usuário

{
  "nome": "Thobias",
  "email": "thobias@email.com",
  "senha": "123456"
}
POSTAR /login
Realize login e retorne token

{
  "email": "thobias@email.com",
  "senha": "123456"
}
POST /mensagens
Cria uma mensagem (token JWT obrigatório no cabeçalho)
Cabeçalho:

Authorization: Bearer SEU_TOKEN_AQUI
Corpo:

{
  "texto": "Minha primeira mensagem"
}
OBTER /mensagens
Lista todas as mensagens cadastradas

🧑‍🏫 Desenvolvido por
Thobias Karpinski – Pós-graduação Inovação e Tecnologia – IFSC
