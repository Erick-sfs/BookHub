# BookHub

## 1. Objetivo do projeto

O BookHub é um projeto voltado à organização de livros e usuários, permitindo registrar informações e controlar empréstimos.

## 2. Pseudo-modelagem do banco de dados

### Usuário
- id: identificador único do usuário
- nome: nome completo
- email: endereço de e-mail

### Livro
- id: identificador único do livro
- titulo: título do livro
- autor: autor do livro
- ano_publicacao: ano de publicação

### Empréstimo
- id: identificador único do empréstimo
- usuario_id: identificador do usuário
- livro_id: identificador do livro
- data_emprestimo: data em que o livro foi emprestado
- data_devolucao: data prevista para devolução

## 3. Relacionamentos

- Um usuário pode realizar vários empréstimos.
- Um livro pode aparecer em vários empréstimos ao longo do tempo.
- Cada empréstimo está associado a um usuário e a um livro.
