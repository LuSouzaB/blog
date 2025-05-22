# 📚 API do Blog – Node.js, Express e SQLite

Este projeto é uma API RESTful para um sistema de blog com cadastro de usuários, autenticação JWT e postagem de mensagens.

---

## 🚀  Tecnologias

- Node.js
- Express.js
- SQLite com Knex.js
- JWT (Token Web JSON)
- bcryptjs

---

# 📦 Como rodar o projeto
```
Clonar o repositório

git clone https://github.com/LuSouzaB/blog.git
cd blog-api

Instalar as dependências
npm install

Criar o banco de dados e tabelas
npm run criar-db

Iniciar o servidor
npm start

```

Uma API estará disponível em:
http://localhost:3000

---

# 🔐 Rotas da API

➡️ POST /inscrição

Cadastrar um novo usuário
```
{
  "nome": "Lucélia",
  "email": "souzabarbosalu@email.com",
  "senha": "654321"
}
```

➡️ POSTAR /login

 Realizar login e retornar token
```
{
  "email": "souzabarbosalu@email.com",
  "senha": "654321"
}

```


 ➡️ POST /mensagens

```

Cria uma mensagem (token JWT obrigatório no cabeçalho)

```

➡️ Corpo:

```
{
  "texto": "Minha primeira mensagem"
}

```


➡️ Obter /mensagens

Lista todas as mensagens cadastradas

---

# 🧑‍🏫 Desenvolvido por

Lucélia Souza Barbosa – Pós-graduação Inovação e Tecnologia – IFSC
