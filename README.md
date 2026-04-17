# U5 Post-Contenido 1 - CRUD con Spring Boot + Repository

## Objetivo
Implementar una API REST de biblioteca usando capas Entity, Repository, Service y Controller con H2 embebida.

## Tecnologias
- Java 17
- Spring Boot 3.2.x
- Spring Web
- Spring Data JPA
- H2 Database
- Validation
- Lombok

## Ejecutar
```bash
mvn clean spring-boot:run
```

## Endpoints
- `POST /api/libros`
- `GET /api/libros`
- `GET /api/libros/{id}`
- `PUT /api/libros/{id}`
- `DELETE /api/libros/{id}`
- `GET /api/libros/buscar?q=texto`

## Verificacion
- Consola H2: `http://localhost:8080/h2-console`
- API base: `http://localhost:8080/api/libros`
