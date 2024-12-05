Here’s the **`README.md`** file:

````markdown
# CRUD API with Spring Boot

This project is a simple CRUD API built with Spring Boot, demonstrating basic REST operations for managing users.

## Features

- **Create**: Add a new user (`POST /users`)
- **Read**:
  - Retrieve all users (`GET /users`)
  - Retrieve a user by ID (`GET /users/{id}`)
- **Update**: Modify an existing user (`PUT /users/{id}`)
- **Delete**: Remove a user (`DELETE /users/{id}`)

## Technologies Used

- **Java**: Backend programming language
- **Spring Boot**: Framework for building the API
- **Maven**: Dependency management and build tool

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven installed

### Running the Application

1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
````

2. Navigate to the project directory:
   ```bash
   cd <project_directory>
   ```
3. Run the application:

   ```bash
   mvn spring-boot:run
   ```

4. The API will be available at:
   ```
   http://localhost:8080
   ```

## Endpoints

| Method   | Endpoint      | Description             |
| -------- | ------------- | ----------------------- |
| `POST`   | `/users`      | Add a new user          |
| `GET`    | `/users`      | Retrieve all users      |
| `GET`    | `/users/{id}` | Retrieve a user by ID   |
| `PUT`    | `/users/{id}` | Update an existing user |
| `DELETE` | `/users/{id}` | Delete a user           |

## Example Request

**Create a User** (`POST /users`):

```json
{
  "name": "John Doe",
  "email": "john@example.com"
}
```

**Update a User** (`PUT /users/{id}`):

```json
{
  "name": "John Smith",
  "email": "johnsmith@example.com"
}
```

## License

This project is open-source and available for modification and distribution.

```

```
