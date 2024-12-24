# SimpleLibraryManagement

This project is a simple Spring Boot application that implements RESTful web services for managing books and authors in a library. It supports common CRUD operations, allowing clients to retrieve, add, update, and delete data. The services are documented using Swagger for ease of exploration and testing.

## Features
- Retrieve a list of authors via an HTTP GET request.
- Retrieve a list of books via an HTTP GET request.
- Add a new book via an HTTP POST request.
- Update the name of a book via an HTTP PUT request.
- Delete a book via an HTTP DELETE request.
- Swagger UI for API documentation and testing.

## Run the project
- Clone the repository
- Setup the database for the books and authors tables
- Run the project application; in case you have an error you need to kill the process that is running on port 8080
Find the process
```
netstat -ano | findstr :8080
```
Kill the process as administrator
```
taskkill /pid <PID> /f
```
- Run the Client application and make sure to put a valid id of a book, in order for the program to work correctly

## Tools and Technologies
- Java
- Spring Boot
- Gradle
- Swagger for API documentation
- JUnit for testing
