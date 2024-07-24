# Backend para Blog Pessoal utilizando Spring Framework

Este repositório contém o código-fonte do backend para um blog pessoal desenvolvido utilizando o framework Spring. O projeto implementa um sistema completo com CRUD (Create, Read, Update, Delete) para tema e categorias, usuários e utilizando relacionamentos `@OneToMany` e `@ManyToOne` para representar a relação entre artigos e seus comentários.



## Funcionalidades Implementadas

- **Autenticação:** Utilização de JWT para autenticação de usuários.
- **Endpoints RESTful:** Criação de endpoints para CRUD de categorias, usuários e comentários, utilizando relacionamentos `@OneToMany` e `@ManyToOne`.
- **Segurança:** Utilização do Spring Security para controle de acesso aos recursos da aplicação.
- **Persistência de Dados:** Utilização do Spring Data JPA para persistência e consulta de dados no banco de dados.

## Testes e Documentação

- **Testes:** Os testes unitários são realizados com JUnit 5, enquanto os testes de integração são executados utilizando o H2 Database.
- **Documentação da API:** Utilize o Swagger para explorar e testar os endpoints da API. Acesse a documentação em [http://localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html).
- **Testado no Insomnia:** O projeto foi testado utilizando o Insomnia para verificar a integridade e o correto funcionamento dos endpoints.

## Tecnologias Utilizadas


![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000.svg?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white) 
![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Spring Web](https://img.shields.io/badge/Spring%20Web-6DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) 
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![H2 Database](https://img.shields.io/badge/H2-4479A1.svg?style=for-the-badge&logo=h2&logoColor=white) 
![JUnit 5](https://img.shields.io/badge/JUnit%205-25A162.svg?style=for-the-badge&logo=JUnit5&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D.svg?style=for-the-badge&logo=Swagger&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=docker&logoColor=white)

- **Java:** Linguagem de programação principal.
- **Spring:** Framework principal utilizado para o desenvolvimento.
- **JWT (JSON Web Token):** Para autenticação e autorização de usuários.
- **Spring Data JPA:** Biblioteca do Spring para acesso e manipulação de dados relacionais no banco de dados.
- **Spring Web:** Utilizado para criar APIs RESTful.
- **Spring Security:** Utilizado para a segurança da aplicação.
- **MySQL:** Banco de dados relacional utilizado para armazenamento de dados.
- **PostgreSQL:** Opção alternativa para adaptação do código para o Render.
- **H2 Database:** Banco de dados em memória utilizado para testes de integração.
- **JUnit 5:** Framework de testes unitários para Java.
- **Swagger:** Utilizado para documentação do código.
- **Docker:** Utilizado para criação de containers e para facilitar a interpretação do Java no Render.

## Como Executar o Projeto

Para executar o projeto localmente, siga os passos abaixo:

1. **Clonar o repositório:**
 git clone https://github.com/rosdrigo/Projeto_blogPessoal.git

2. **Configurar o Banco de Dados:**
- Utilize MySQL ou PostgreSQL e configure as credenciais no arquivo `application.properties`.

3. **Executar com Docker:**
- Utilize o Docker para criar um container com a aplicação e o banco de dados.

4. **Documentação da API:**
- Acesse a documentação da API gerada pelo Swagger em [http://localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html).

5. **Testes:**
- Execute os testes unitários com JUnit 5 e os testes de integração utilizando o H2 Database.

## Deploy no Render

Este projeto está configurado para deploy no Render. Utilize o Docker para criar um container que possa ser interpretado pelo Render.



