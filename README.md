# Eureka Service

## Description
This microservice provides a service registry and discovery functionality, allowing microservices to register themselves and discover other services in the ecosystem.

## Features
- Service registration and discovery
- Health checks for registered services
- Load balancing for requests

## API Endpoints
| Method | Endpoint                | Description                       |
|--------|-------------------------|-----------------------------------|
| GET    | `/eureka/apps`          | List all registered applications   |
| GET    | `/eureka/apps/{serviceName}` | Get details of a specific service |

## Technologies Used
- Spring Cloud Netflix Eureka
- Spring Boot

## Installation
1. Clone the repository.
2. Run `mvn clean install` to build the project.
3. Configure your application properties (including server port and instance metadata).
4. Run the application using your IDE or with `mvn spring-boot:run`.

## License
This project is licensed under the License Apache 2.0.
