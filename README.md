# Organica – Full-Stack E-Commerce Application

Organica is a full-stack e-commerce web application designed for
online shopping and product management. The application provides
user authentication, product browsing, cart management, and a
responsive shopping interface.

## Features

- User Registration and Login
- JWT-based Authentication
- Product Listing and Product Details
- Shopping Cart Management
- Add and Remove Products from Cart
- Product Image Handling
- RESTful APIs
- MySQL Database Integration
- Responsive React Frontend

## Technology Stack

### Frontend
- React.js
- JavaScript
- HTML5
- CSS3
- Axios

### Backend
- Java
- Spring Boot
- Spring Security
- REST APIs
- JWT Authentication
- Maven

### Database
- MySQL

### Tools
- Git
- GitHub
- Visual Studio Code

## Project Structure

Organica/
│
├── Client/        # React frontend
├── Server/        # Spring Boot backend
├── init/          # Initial project/database resources
├── docker-compose.yml
└── README.md

## Application Architecture

The application follows a client-server architecture:

React Frontend → REST API → Spring Boot Backend → MySQL Database

The frontend communicates with the backend using HTTP requests
through REST APIs. The Spring Boot backend handles business logic,
authentication, product management, and cart operations, while
MySQL stores application data.

## Authentication

The application uses Spring Security with JWT-based authentication.
Passwords are securely handled using BCrypt password encoding.

## Key Functional Modules

### User Management
- User registration
- User login
- Authentication
- JWT token generation

### Product Management
- Product listing
- Product details
- Product image handling
- Product data retrieval

### Cart Management
- Add products to cart
- View cart items
- Remove cart items
- Cart-related operations

## Future Enhancements

- Online payment integration
- Admin dashboard
- Order management
- Product search and filtering
- Deployment using cloud services

## Author

Rishitha Reddy
