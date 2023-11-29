# back-end-tf-web
“Back-End do trabalho final da disciplina de WEB”

## Integrantes 

- [Iane Gabriela Ferreira Miranda](https://github.com/ianemiranda)
- [Claudielia Pereira de Almeida](https://github.com/cpa9almeida)
- [Allana Vitoria Nunes]()
- [Maria Isabel Carmo Lopes](https://github.com/izinhah)


### Documentação
[Link da imagem do Modelo-Conceitual]()

### - Funções de Usuários:
 
 - Cadastrar novo usuário:

 Descrição: Inserir um novo usuário no banco de dados.

 Endpoint: 

 Tipo de requisição: POST

 Body:
 {
  "nome": "Nome do usuário",
  "senha": "***"
  "email": "email.usuario@gmail.com"
 }

 - Listar todos os usuários e as suas informações:

 Descrição: Listar todos os usuários e suas informações:

 Endpoint:

 Tipo de requisição: GET

 Body: não há

 - Listar as informações de apenas um usuário:

 Descrição: Alterar as informações de um único usuário.

 Endpoint:

 Tipo de requisição: PATCH

 Body:
 {
    "id" 1,
    "nome": "Nome do usuário",
    "senha": "***"
    "email": "email.usuario@gmail.com"
 }

 - Excluir as informações de apenas um usuário:

 Descrição: Excluir as informações de apenas um usuário.

 Endpoint

 Tipo de requisição: DELETE

 Body:
 {
    "_id": 1
 }

 - Autenticar o usuário: 

 Descrição: Conferir se o usuário está usando a aplicação.

 Endpoint: 

Tipo de requisição: GET

Body: não há

------

### - Funções do Admin:

- Cadastrar novo admin:

Descrição: Inserir um novo admin no banco de dados.

Endpoint:

Tipo de requisição: POST

Body:
{
    "nome": "Nome do admin",
    "senha": "***".
    "email": "email.admin@gmail.com"
}


- Listar todos os admins e suas informações:

Descrição: Listar todos os usuários e suas informações.

Endpoint:

Tipo de requisição: GET

Body: não tem

- Listar as informações de apenas um admin:

Descrição: Modificar as informações de um admin.

Endpoint:

Tipo de requsição: PATCH

Body:
{
    "id": 1,
    "nome": "Nome do admin",
    "senha": "***",
    "email": "email.admin@gmail.com"
}

- Excluir as informações de um admin:

Descrição: Excluir as informações de um admin.

Endpoint:

Tipo de requisição: DELETE

Body:
{
  "_id": 1
}

- Autenticar o admin:

Descrição: Conferir se o admin está usando a apliicação.

Endpoint:

Tipo de requisição: GET

Body: não tem

