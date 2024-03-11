# Blog App Fronted







# Blog App Web Application

## Introduction -
This project is a Blog App web application developed using Java, Spring Boot, Angular, Spring Security, JWT Authentication, and MySQL. It provides users with functionalities to create, read, update, and delete blog posts, as well as authentication and authorization features to secure the application.

## Technologies -
- **Java**: Programming language used for backend development.
- **Spring Boot**: Framework for building Java-based web applications.
- **Angular**: Frontend framework for building dynamic web applications.
- **Spring Security**: Provides authentication, authorization, and other security features.
- **JWT (JSON Web Tokens)**: Used for stateless authentication by generating and verifying tokens.
- **MySQL**: Relational database management system for storing application data.

## Features -
- User Registration: Allows users to create new accounts with unique usernames and passwords.
- User Authentication: Secure authentication using JWT tokens.
- Blog Post Management: Enables users to create, read, update, and delete their blog posts.
- Authorization: Restricts access to certain functionalities based on user roles (e.g., admin, regular user).
- Password Encryption: Safely stores user passwords using encryption techniques.
- Responsive Design: Provides a user-friendly experience across different devices and screen sizes.

## Architecture -
The application follows a standard client-server architecture:
- **Backend (Server)**: Developed using Java and Spring Boot, it handles business logic, data storage, and authentication/authorization.
- **Frontend (Client)**: Built using Angular, it provides the user interface for interacting with the application.
- **Database**: MySQL is used as the database management system to store blog posts, user information, and other data.

## Modules -
The key modules of the application include:
- **Authentication Module**: Implements user registration, login, and JWT token generation.
- **Blog Module**: Manages the creation, retrieval, updating, and deletion of blog posts.
- **User Module**: Handles user-related functionalities such as profile management and password reset.
- **Security Module**: Configures Spring Security to secure endpoints and enforce access control.















## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
