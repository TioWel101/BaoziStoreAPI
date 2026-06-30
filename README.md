# Baozi Store API

REST API developed for the Web Back-End course using Spring Boot.

## Technologies

- Java 21
- Spring Boot 3
- Spring Data JPA
- H2 Database
- Maven

## Endpoints

### Customer

- POST /clientes
- GET /clientes
- GET /clientes/{id}
- DELETE /clientes/{id}

### Product

- POST /produtos
- GET /produtos
- GET /produtos/{id}
- DELETE /produtos/{id}

### Order

- POST /pedidos
- GET /pedidos
- GET /pedidos/{id}
- DELETE /pedidos/{id}

## Running

```bash
mvn spring-boot:run