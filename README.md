# Todo aapp microservices application

## Table of contents

- [Todo list microservices architecture application](#Todo-list-microservices-architecture-application)
  - [Table of contents](#Table-of-contents)
  - [Description](#Description)
  - [Project structure](#Project-structure)
  - [Cloning repository](#Cloning-repository)
  - [Prerequisites](#Prerequisites)
  - [Technology stack](#Technology-stack)
    - [User service technology stack](#User-service-technology-stack)
    - [Todo service technology stack](#Todo-service-technology-stack)
    - [Gateway API service technology stack](#Gateway-API-service-technology-stack)
    - [End2end tests technology stack](#End2end-tests-technology-stack)
  - [Diagrams](#Diagrams)
    - [Deployment diagram](#Deployment-diagram)
    - [Login user sequence diagram](#Login-user-sequence-diagram)
    - [Register user sequence diagram](#Register-user-sequence-diagram)
    - [Create todo sequence diagram](#Create-todo-sequence-diagram)
    - [Get todo sequence diagram](#Get-todo-sequence-diagram)
    - [Delete todo sequence diagram](#Delete-todo-sequence-diagram)
    - [Update todo sequence diagram](#Update-todo-sequence-diagram)
    - [List todo sequence diagram](#List-todo-sequence-diagram)

## Description

This project demonstrates microservices architecture based application.

Main application features:

- users can create, list, update and delete tasks
- services use different databases.

Application consists of three services:

- User service - Create, update, delete, and show all users
- Tasks service - Create, update, and delete taks. This service can show all tasks of a user as well

## Project structure

```
.
├── tasks-microservice - directory with source code for task service
└── user-microservice - directory with source code for user service
```

## Cloning repository

```bash
git clone --recurse-submodules https://github.com/Jhon112/todo-app-microservices
```

## Technology stack

### User service technology stack

- Python3
- Flask
- SQLAlchemy
- MySQL

### Tasks service technology stack

- Ruby
- Ruby on Rails - API
- Postgresql

<!-- ## Diagrams

### Deployment diagram

![Deployment diagram](/docs/diagrams/out/deployment_diagram.png?raw=true) -->
