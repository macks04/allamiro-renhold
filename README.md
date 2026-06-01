# Allamiro Renhold

Prototype for a planning and customer management system for small cleaning businesses.

## About the Project

This project was developed as part of a bachelor's thesis at the University of South-Eastern Norway (USN).

The goal of the project is to provide a simple digital solution for managing:

* customers
* employees
* cleaning jobs
* customer requests
* automatic message generation

The system was designed for a small local cleaning company that previously handled planning manually.

---

## Technologies Used

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Spring Boot
* REST API
* PostgreSQL
* Spring Data JPA

### Other Tools

* GitHub
* pgAdmin 4
* VS Code

---

## Features

* Customer management
* Employee management
* Job planning
* Customer request registration
* Message generator
* Dashboard overview
* Backend API integration
* PostgreSQL database connection

---

## Backend and Database

A Spring Boot backend was implemented and connected to a PostgreSQL database.

The project includes:

* PostgreSQL database tables
* REST API endpoint for customer data
* Frontend communication using `fetch()`
* JSON responses from backend to frontend

Example endpoint:

```text
http://localhost:8080/api/customers
```

---

## Database Tables

The PostgreSQL database currently contains:

* customers
* employees
* jobs
* requests

---

## Future Development

Possible future improvements:

* Authentication and login system
* Full CRUD API for all entities
* Better role management
* Cloud hosting
* Improved frontend design
* Full replacement of localStorage with backend persistence

---

## GitHub Repository

Repository created for version control and project documentation during development.

---

## Authors

Bachelor project developed by:

* Maksim Kurakin
* Lukas
