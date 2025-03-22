# Day02

# Spring Boot Application - Simple REST Controller

This is a simple Spring Boot application that provides REST API endpoints.

## Project Structure

```
lk.vau.ac.fas.ict.controller
│── AppController.java
```

## Features

- Exposes RESTful endpoints using Spring Boot.
- Handles HTTP `GET` requests.

## Installation

1. Clone this repository:
   ```sh
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```sh
   cd <project-directory>
   ```
3. Build and run the application using Maven or your preferred method:
   ```sh
   mvn spring-boot:run
   ```

## API Endpoints

| HTTP Method | Endpoint       | Description                      |
|------------|---------------|----------------------------------|
| GET        | `/app/name`   | Returns "Hello SpringBoot."     |
| GET        | `/app/profile` | Returns "Hello my name is Oshan." |

## Technologies Used

- Java
- Spring Boot
- Maven

## Author

- **Oshan**

## License

This project is licensed under the MIT License.

