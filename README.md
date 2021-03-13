# Todo List - Desafio Principal 1

Desafio com o intuito de fixar os conceitos iniciais de API Rest com Node.js e Express

## Entidades

| Entidades | Atributos |
| - | - |
| user | id, name, username, todos |
| todo | id, title, done, deadline, created_at |

## Requisitos

- [ ] Deve ser possível cadastrar um usuário
- [ ] Deve ser possível listar as tarefas de um usuário
- [ ] Deve ser possível cadastrar uma tarefa de um usuário
- [ ] Deve ser possível editar o título e a deadline de uma tarefa
- [ ] Deve ser possível marcar uma tarefa como realizada
- [ ] Deve ser possível deletar uma tarefa

## Regras de negócio

- [ ] Não deve ser possível criar um usuário com um username já cadastrado
- [ ] Não deve ser possível listar tarefas de um usuário que não existe
- [ ] Não deve ser possível cadastrar tarefas para um usuário que não existe
- [ ] Não deve ser possível editar tarefas de um usuário que não existe
- [ ] Não deve ser possível editar tarefas que não exitem
- [ ] Não deve ser possível marcar uma tarefa como realizada de um usuário que não existe
- [ ] Não deve ser possível marcar uma tarefa que não existe como realizada
- [ ] Não deve ser possível deletar tarefas de um usuário que não existe
- [ ] Não deve ser possível deletar tarefas que não exitem

## Recursos

- Express
- Dados armazenados em memória

## Iniciando o projeto

Após clonar o projeto, é necessário atualizar as dependências.

### Comandos para baixar dependências e iniciar a aplicação

```bash
yarn
yarn dev
```

### Testar a aplicação

```bash
yarn test
```