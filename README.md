# Student Registration System

A Spring Boot full-stack web application built with Spring Initializr, Spring Data JPA, H2 Database, Thymeleaf, and Spring Boot Validation[cite: 1].

## Features
- **Create**: Add new student records with form validation (Name, Email, Phone, Course, Age)[cite: 1, 2].
- **Read**: View all registered students in a responsive data table[cite: 1, 2].
- **Update**: Edit existing student details[cite: 1, 2].
- **Delete**: Remove student records from the H2 database[cite: 1, 2].
- **Persistence**: Supports both in-memory and file-based H2 database configurations[cite: 20].

## Prerequisites
- JDK 17 or JDK 21[cite: 3]
- Maven (bundled via Maven Wrapper `mvnw`)[cite: 3]

## How to Run
1. Clone the repository.
2. Run the application using the Maven wrapper:
   - On Windows: `mvnw.cmd spring-boot:run`
   - On Linux/macOS: `./mvnw spring-boot:run`
3. Open your web browser and navigate to: `http://localhost:8080/students`[cite: 2]