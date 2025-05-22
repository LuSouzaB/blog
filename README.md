# 📚 API do Blog – Node.js, Express e SQLite

Este projeto é uma API RESTful para um sistema de blog com cadastro de usuários, autenticação JWT e postagem de mensagens.

---

## 🚀 Tecnologias

- Node.js
- Express.js
- SQLite com Knex.js
- JWT (Token Web JSON)
- bcryptjs

---

## 📦 Como rodar o projeto

---

🔐 Rotas da API

---

## 🔐 Rotas da API

### ➡️ POST /inscrição  
**Cadastrar um novo usuário**  

```json
{
  "nome": "Lucélia",
  "email": "souzabarbosalu@email.com",
  "senha": "654321"
}
➡️ POST /login
Realizar login e retornar token

'''json

{
  "email": "souzabarbosalu@email.com",
  "senha": "654321"
}

➡️ POST /mensagens
Cria uma mensagem (token JWT obrigatório no cabeçalho)

Cabeçalho:

makefile

Authorization: Bearer SEU_TOKEN_AQUI
Corpo:

'''json

{
  "texto": "Minha primeira mensagem"
}

➡️ Obter /mensagens
Lista todas as mensagens cadastradas
--- 

🧑‍🏫 Desenvolvido por
Lucélia Souza Barbosa – Pós-graduação Inovação e Tecnologia – IFSC
