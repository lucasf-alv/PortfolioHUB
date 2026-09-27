# ExperienceProject

Projeto de desenvolvimento de uma plataforma de atividades e experiências, desenvolvido com o objetivo de praticar conceitos de desenvolvimento backend, frontend, banco de dados, autenticação e integração entre serviços.

## Objetivo

O ExperienceProject permite o gerenciamento de atividades e experiências, possibilitando a criação, participação e acompanhamento dessas atividades pelos usuários.

O projeto também utiliza um sistema de experiência (XP) e níveis para registrar a evolução dos usuários dentro da plataforma.

## Tecnologias

### Backend

* Java
* Spring Boot
* Spring Security
* Spring Data JPA
* PostgreSQL
* Liquibase
* JWT

### Frontend

* React
* TypeScript
* Vite
* Tailwind CSS
* Leaflet

### Infraestrutura

* Docker
* Docker Compose
* PostgreSQL
* LocalStack
* Amazon S3

## Funcionalidades

* Cadastro de usuários
* Autenticação
* Gerenciamento de atividades
* Participação em atividades
* Registro de participantes
* Sistema de experiência (XP)
* Sistema de níveis
* Preferências dos usuários
* Conquistas
* Integração com armazenamento de arquivos
* Visualização de atividades utilizando mapas

## Estrutura do projeto

O projeto é dividido principalmente em:

```text
ExperienceProject/
├── backend/
├── frontend/
└── docker-compose.yml
```

O backend concentra a API e as regras de negócio, enquanto o frontend é responsável pela interface da aplicação.

## Sistema de XP

O projeto possui um sistema de pontuação baseado na participação dos usuários nas atividades.

A pontuação é utilizada para representar a evolução do usuário e determinar seu nível dentro da plataforma.

## Objetivos de aprendizado

Este projeto foi desenvolvido para praticar:

* Desenvolvimento de APIs REST
* Arquitetura de aplicações
* Autenticação e autorização
* Persistência de dados
* Modelagem de banco de dados
* Migrations com Liquibase
* Desenvolvimento frontend
* Integração entre frontend e backend
* Containerização
* Integração com serviços de armazenamento

## Repositório

O código-fonte do projeto está disponível no GitHub:

https://github.com/lucasf-alv/ExperienceProject
