# JWT Authentication System

## Overview

This project demonstrates a **secure role-based authentication and authorization system** using **.NET Web API** and **Angular**. It implements **JWT (JSON Web Token)** authentication to protect routes and manage user access based on roles.

---

## Features

* JWT-based authentication
* Role-based authorization
* User registration and login
* Protected API endpoints
* Role management
* Angular frontend integration
* Secure API communication

---

## Tech Stack

### Backend

* ASP.NET Core Web API
* Entity Framework Core
* SQLite / SQL Server

### Frontend

* Angular
* Angular Material / Tailwind CSS

### Authentication

* JSON Web Tokens (JWT)

---

## Prerequisites

* .NET SDK
* Node.js & npm
* Angular CLI
* Database (SQLite or SQL Server)

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/joemickie/jwt-authentication.git
cd jwt-authentication
```

---

### 2. Run Backend (API)

```bash
cd API
dotnet watch run
```

---

### 3. Run Frontend (Client)

```bash
cd client
npm install
ng serve
```

---

## Project Structure

```
jwt-authentication/
│
├── API/            # .NET Web API
├── client/         # Angular Frontend
├── README.md
```

---

## Key Functionality

* Secure login and registration
* JWT token generation and validation
* Role-based access control (e.g., Admin, User)
* Protected routes in Angular
* API authorization using middleware

---

## Notes

* Ensure backend is running before starting frontend

---

## License

This is a personal project
