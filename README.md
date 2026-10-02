# Support Issue Management System

## About the Project

The Support Issue Management System is a backend application developed using Java and Spring Boot.

The main purpose of this project is to provide a simple way to manage support issues. Users can create a new issue, view existing issues, update issue details, and delete issues when they are no longer required.

The application uses REST APIs to handle requests and MySQL to store the issue information.

## Features

- Create a new support issue
- View support issues
- Update an existing issue
- Delete an issue
- Store issue details in MySQL
- REST API based backend
- Unit testing for application operations
- Maven for project management and dependencies

## Technologies Used

- Java
- Spring Boot
- REST APIs
- MySQL
- Maven
- Unit Testing
- Postman

## How the Project Works

The project follows a simple layered architecture.

The request first comes to the Controller. The Controller sends the request to the Service layer, where the application logic is handled. The Repository layer then communicates with the MySQL database.

The basic flow is:

Client → Controller → Service → Repository → MySQL

The response follows the same flow back to the client.

## API Operations

The application provides REST APIs for the following operations:

| Method | Operation |
|--------|-----------|
| POST | Create a support issue |
| GET | View support issues |
| PUT | Update a support issue |
| DELETE | Delete a support issue |

The APIs can be tested using Postman.

## Project Structure

```text
src
├── main
│   ├── java
│   │   └── controller
│   │   ├── dao
│   │   ├── model
│   │   └── service
│   │
│   └── resources
│       └── application.properties
│
└── test
    └── java
        └── Unit Test Classes












