# Dummy Blog

A simple blog web-app, built with Django.

## ERD

```mermaid
erDiagram
    User {
        string username
        string email
        string password
    }    
    Post {
        string title
        string author
        string body
    }
    User ||--o{ Post : creates
```

## About

Dummy Blog is a web-app for users to pour their thoughts in a simple manner. It supports basic authentication and multiple users.

## Built With

![Django Badge](https://img.shields.io/badge/django-0e3c27?logo=django&style=flat)
![Python](https://img.shields.io/badge/python-18314c?logo=python&style=flat)
![SQLite](https://img.shields.io/badge/sqlite-669585?logo=sqlite&style=flat)
![PostgreSQL](https://img.shields.io/badge/postgresql-588cbf?logo=postgresql&style=flat&logoColor=white)
![HTML](https://img.shields.io/badge/html-db341a?logo=html5&style=flat&logoColor=white)
![CSS](https://img.shields.io/badge/css-black?logo=css3&style=flat)
![JavaScript](https://img.shields.io/badge/js-f5db15?logo=javascript&style=flat&logoColor=white)
![Docker](https://img.shields.io/badge/docker-1747e8?logo=docker&style=flat)
