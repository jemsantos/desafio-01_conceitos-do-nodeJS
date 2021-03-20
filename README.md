# Desafio-01_Conceitos-do-NodeJS
Desafio sobre Fundamento e Conceitos do NodeJS aplicado no Bootcamp Ignite

# Descrição:
Nesse desafio, será criada uma aplicação para treinar o que já foi aprendido no Node.js!

Essa será uma aplicação para gerenciar tarefas (em inglês *todos*). Será permitida a criação de um usuário com `name` e `username`, bem como fazer o CRUD de *todos*:

- Criar um novo *todo*;
- Listar todos os *todos*;
- Alterar o `title` e `deadline` de um *todo* existente;
- Marcar um *todo* como feito;
- Excluir um *todo*;

Tudo isso para cada usuário em específico (o `username` será passado pelo header). A seguir veremos com mais detalhes o que e como precisa ser feito 🚀

# Rotas da aplicação

- POST /users
- GET /todos
- POST /todos
- PUT /todos/:id
- PATCH /todos/:id/done
- DELETE /todos/:id

# Específicação dos testes

## Testes de usuários

- **Should be able to create a new user**
- **Should not be able to create a new user when username already exists**

## Testes de todos

- **Should be able to list all user's todos**
- **Should be able to create a new todo**
- **Should be able to update a todo**
- **Should not be able to update a non existing todo**
- **Should be able to mark a todo as done**
- **Should not be able to mark a non existing todo as done**
- **Should be able to delete a todo**
- **Should not be able to delete a non existing todo**





