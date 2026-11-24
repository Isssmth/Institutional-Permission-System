# Institutional Permission System
Starter scaffold using Java 25, Spring Boot 3.5.6, Maven, Spring Data JPA, Spring Security, validation, and MySQL.

## Setup
1. Create database: `CREATE DATABASE institutional_permission_db;`
2. Set environment variable `DB_PASSWORD` to your local MySQL password. Never commit passwords.
3. Open this folder in VS Code and run `PermissionApplication.java`, or run `mvn spring-boot:run`.
4. Server port: 8080.

This is a starter structure only. Login, dashboards, permissions, and workflow logic are not implemented yet.

Frontend decision: `templates/` and `static/` are placeholders for a Spring-rendered UI. If using React, create a separate `frontend/` app and keep this project as the API backend.
