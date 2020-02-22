# Todo app microservices application

## Table of contents

- [Todo list microservices architecture application](#Todo-app-microservices-architecture-application)
  - [Table of contents](#Table-of-contents)
  - [Description](#Description)
  - [Project structure](#Project-structure)
  - [Cloning repository](#Cloning-repository)
  - [Technology stack](#Technology-stack)
    - [User service technology stack](#User-service-technology-stack)
    - [Tasks service technology stack](#Tasks-service-technology-stack)

  <!-- - [Diagrams](#Diagrams)
    - [Deployment diagram](#Deployment-diagram) -->


## Description

This project demonstrates microservices architecture based application.

Main application features:

- users can create, list, update and delete tasks
- services use different databases.

Application consists of three services:

- User service - Create, update, delete, and show all users
- Tasks service - Create, update, and delete taks. This service can show all tasks of a user as well

Live servers:

- User interface (React app) - <https://to-do-app-904.herokuapp.com/>
- User service - <https://user-microservices.herokuapp.com/api/v1/status>
- Tasks service - <https://tasks-microservice-904.herokuapp.com/api/v1/tasks/1>

## Project structure

```
.
├── tasks-microservice - directory with source code for task service
└── user-microservice - directory with source code for user service
└── To-do-FrontEnd - directory with source code containing react app that connects both microservices
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
- Postgresql

### Tasks service technology stack

- Ruby
- Ruby on Rails - API
- Postgresql

## Diagrams

### Architecture diagram

![App architecture diagram](https://github.com/Jhon112/todo-app-microservices/todo-app.png?raw=true)
