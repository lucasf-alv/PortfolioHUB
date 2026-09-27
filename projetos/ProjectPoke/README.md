# ProjectPoke

Projeto desenvolvido para estudar integração entre agentes de inteligência artificial, servidores MCP (Model Context Protocol), APIs e aplicações web.

## Objetivo

O ProjectPoke utiliza um agente de inteligência artificial integrado a um servidor MCP para consultar informações de Pokémon através da PokeAPI.

O projeto também possui uma aplicação frontend responsável pela interação com o usuário.

## Tecnologias

### Agent

* TypeScript
* Node.js
* OpenAI Agents SDK
* Ollama
* Qwen
* MCP

### MCP Server

* TypeScript
* Node.js
* Model Context Protocol
* Zod
* PokeAPI

### Frontend

* React
* TypeScript
* Vite

## Arquitetura

O projeto é dividido em três partes principais:

```text
ProjectPoke/
├── agent/
├── frontend/
└── mcp-server/
```

### Agent

Responsável pela comunicação com o modelo de inteligência artificial e pela utilização das ferramentas disponibilizadas pelo servidor MCP.

### MCP Server

Disponibiliza ferramentas para consulta de informações da PokeAPI.

### Frontend

Interface web utilizada para interagir com o sistema e apresentar as informações dos Pokémon.

## MCP

O Model Context Protocol permite que o agente utilize ferramentas e fontes de dados externas de maneira padronizada.

Neste projeto, o MCP Server disponibiliza funcionalidades relacionadas à consulta de Pokémon para o agente.

## Funcionalidades

* Consulta de Pokémon
* Integração com PokeAPI
* Agente de inteligência artificial
* Comunicação utilizando MCP
* Consulta de informações através de ferramentas
* API HTTP para comunicação com o frontend
* Interface web para apresentação dos dados

## Exemplo

O sistema pode receber uma solicitação para consultar um Pokémon, utilizar o agente e o servidor MCP para realizar a consulta e retornar informações como:

* Nome
* Número
* Tipo
* Habilidades
* Altura
* Peso
* Estatísticas
* Imagem

## Objetivos de aprendizado

Este projeto foi desenvolvido para praticar:

* TypeScript
* Desenvolvimento de APIs
* Integração com APIs externas
* Inteligência artificial
* Agentes
* Model Context Protocol
* Arquitetura cliente-servidor
* Desenvolvimento frontend
* Integração entre serviços

## Repositório

O código-fonte do projeto está disponível no GitHub:

https://github.com/lucasf-alv/ProjectPoke
