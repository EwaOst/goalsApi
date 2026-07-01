# Personal Goals & Habit Tracker API

A RESTful application built with **Java 17** and **Spring Boot** that helps users manage personal goals, build habits, track progress, and receive reminders.

The project follows a layered architecture, separating controllers, services, repositories, and DTOs to provide a clean and maintainable backend.

## Features

- User management
- Goal management (CRUD operations)
- Habit management with configurable tracking frequency
- Progress tracking
- Reminder support
- Statistics and progress analysis
- Request validation
- DTO-based data transfer
- Database versioning with Liquibase
- Unit tests for REST controllers

## Project Architecture

The application follows a layered architecture:

- **Controllers** – expose REST endpoints and process HTTP requests.
- **Services** – implement business logic.
- **Repositories** – provide data access using Spring Data JPA.
- **Models** – represent the application's domain entities.
- **DTOs** – separate API contracts from domain models.

## Main Entities

- User
- Goal
- Habit
- Reminder
- Statistics

## Technologies

- Java 17
- Spring Boot 3
- Spring Web
- Spring Data JPA
- Hibernate
- Spring Validation
- Spring Mail
- Thymeleaf
- Liquibase
- H2 Database
- Lombok
- JUnit 5
- Mockito
- MockMvc
- Maven

## Example Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | `/goals` | Create a new goal |
| GET | `/goals/{id}` | Retrieve a goal by ID |
| PUT | `/goals/{id}` | Update an existing goal |
| DELETE | `/goals/{id}` | Delete a goal |

Additional REST endpoints are available for managing users, habits, reminders, and statistics.

## Project Goal

The project demonstrates backend development with Spring Boot by implementing a RESTful application for tracking habits and personal goals. It includes CRUD operations, layered architecture, request validation, database versioning with Liquibase, reminder functionality, and controller unit testing.
