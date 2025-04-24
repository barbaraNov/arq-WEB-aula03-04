# 📋 API de Gerenciamento de Tarefas

Projeto desenvolvido com **Spring Boot**, utilizando arquitetura em camadas para gerenciamento de tarefas. Permite criar, listar, atualizar e excluir tarefas, com suporte a bancos relacionais e NoSQL.

## 🚀 Tecnologias

- Java 17
- Spring Boot (Web, Data JPA, Data MongoDB, DevTools)
- H2, MariaDB, MongoDB
- Lombok
- Maven

## 🔧 Funcionalidades

- Criar tarefa – `POST /tarefas`
- Listar tarefas – `GET /tarefas`
- Atualizar tarefa – `PUT /tarefas/{id}`
- Excluir tarefa – `DELETE /tarefas/{id}`

## ⚙️ Banco de Dados

Configuração via `application.properties`, com suporte a:

- **H2** (em memória)
- **MariaDB** (relacional)
- **MongoDB** (NoSQL)

## ▶️ Como executar

```bash
./mvnw spring-boot:run
