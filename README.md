# 🛡️ Insurance Claim Management App

This is a full-stack **Insurance Claim Management Application** designed to streamline the process of submitting, reviewing, and processing insurance claims. The application enables users to register, log in securely, and file insurance claims which are then reviewed by authorized personnel within the system. The project integrates **Angular** for the frontend and **Spring Boot** for the backend, with robust security provided by **Spring Security** and **JWT (JSON Web Tokens)** for authentication and authorization.

---

## 🚀 Features

- **User Authentication & Authorization**
  - Secure login and registration using JWT-based authentication.
  - Role-based access control managed with Spring Security.
  - Stateless sessions using access tokens.

- **Claim Submission and Tracking**
  - Users can file new insurance claims via the frontend interface.
  - Claims include essential details and can optionally support attachments.
  - Users can track the status of their submitted claims.

- **Modern UI**
  - Responsive, user-friendly interface built with Angular.
  - Clean design focused on usability and efficient interaction.

---

## 🛠️ Tech Stack

### Frontend
- [Angular](https://angular.io/)
- Angular Router
- Reactive Forms
- HTTPClientModule

### Backend
- [Spring Boot](https://spring.io/projects/spring-boot)
- Spring Web (REST API)
- Spring Security
- JWT (JSON Web Token)
- Spring Data JPA
- Database: PostgreSQL

## 🔐 Security

- JWT (JSON Web Token) is used to manage authentication securely.
- Passwords are hashed before being persisted.
- Spring Security enforces role-based permissions at both endpoint and method levels.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.
