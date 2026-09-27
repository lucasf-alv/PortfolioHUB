# MyBank

Projeto de aplicação bancária desenvolvido para praticar conceitos de desenvolvimento de software, APIs, banco de dados, autenticação e desenvolvimento de aplicações mobile.

## Objetivo

O MyBank tem como objetivo simular funcionalidades de uma aplicação bancária, permitindo trabalhar com operações financeiras e gerenciamento de usuários.

O projeto está sendo desenvolvido com uma arquitetura separando a aplicação mobile do backend responsável pelas regras de negócio e persistência dos dados.

## Tecnologias

### Backend

* Java
* Spring Boot
* Spring Data JPA
* Spring Security
* PostgreSQL
* Liquibase
* Bean Validation
* Lombok

### Aplicação mobile

* React Native
* Expo
* TypeScript

## Funcionalidades

O projeto está sendo desenvolvido com funcionalidades relacionadas a:

* Cadastro de usuários
* Gerenciamento de contas
* Autenticação
* Operações bancárias
* Transferências via PIX
* Gerenciamento de chaves PIX
* Validação de dados
* Tratamento de exceções
* Persistência de dados

## Estrutura do projeto

```text
MyBank/
├── backend/
│   └── mybank/
└── aplicação mobile/
```

O backend concentra a API, as regras de negócio, a segurança e a comunicação com o banco de dados.

A aplicação mobile será responsável pela interface utilizada pelo usuário.

## Banco de dados

O projeto utiliza PostgreSQL para persistência dos dados.

As alterações da estrutura do banco são controladas utilizando Liquibase, permitindo versionar as mudanças realizadas no banco de dados.

## PIX

Uma das funcionalidades trabalhadas no projeto é o sistema de PIX, incluindo o gerenciamento de chaves e as operações relacionadas às transferências.

## Objetivos de aprendizado

Este projeto foi desenvolvido para praticar:

* Desenvolvimento de APIs REST
* Desenvolvimento mobile
* Spring Boot
* Persistência com JPA
* Modelagem de banco de dados
* Migrations com Liquibase
* Validação de dados
* Tratamento de exceções
* Autenticação e segurança
* Desenvolvimento de sistemas financeiros

## Repositório

O código-fonte do projeto está disponível no GitHub:

https://github.com/lucasf-alv/MyBank
