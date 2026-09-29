# Helpdesk API

REST API para gestionar tickets de soporte técnico, construida con Spring Boot.
Proyecto 1 de 3 de mi ruta de aprendizaje de Java, con enfoque en seguridad.

## Stack
- Java 21
- Spring Boot (Web, Data JPA, Validation)
- H2 (base de datos en memoria)
- Maven

## Cómo correrlo
```bash
./mvnw spring-boot:run
```
La API queda en `http://localhost:8080`.

## Endpoints
| Método | Ruta        | Descripción        |
|--------|-------------|--------------------|
| GET    | /api/ping   | Health check       |

## Roadmap
- [ ] CRUD de tickets
- [ ] Validación de entradas y manejo global de errores
- [ ] Tests con JUnit y MockMvc
- [ ] PostgreSQL