# Spring Boot To-Do List API

This is a simple To-Do List REST API built with Spring Boot. You can create, read, update, and delete tasks using HTTP requests.

## Running the Project

1. Clone the repository to your local machine.
2. Navigate to the project folder in your terminal.
3. Run `mvn spring-boot:run` to start the application.
4. Access the API at `http://localhost:8080/api/todos`.

## API Endpoints

- `GET /api/todos`: Retrieve all to-do items.
- `POST /api/todos`: Create a new to-do item.
- `PUT /api/todos/{id}`: Update a to-do item.
- `DELETE /api/todos/{id}`: Delete a to-do item.
