# FórumHub API

FórumHub é uma API REST desenvolvida em Spring Boot para um fórum de discussão, permitindo a criação, listagem, atualização e exclusão de tópicos.

##  Funcionalidades

- CRUD de tópicos
- Validação de tópicos duplicados (mesmo título e mensagem)
- Verificação de ID ao detalhar um tópico

## Tecnologias

As seguintes tecnologias foram utilizadas no desenvolvimento da API Rest do projeto:

- Java 17
- Spring Boot 3
- Spring Security
- JWT (JSON Web Token)
- Maven
- MySQL
- Hibernate
- Flyway
- Lombok

##  Autenticação

Para interagir com a API, é necessário autenticar-se utilizando tokens JWT (JSON Web Token):

- Acesse a rota `http://localhost:8080/login` para obter um token JWT válido.
- Inclua o token JWT no cabeçalho de autorização de todas as requisições subsequentes.
- Utilize a biblioteca JWT.io para gerenciar tokens JWT na sua aplicação.







