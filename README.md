# Pinda TMS - Java Backend

This is a **Spring Boot**-based **Transport Management System (TMS)**, featuring **OMS (Order Management System)** and **User Management**.

## Project Structure

- `backend/` - Java Spring Boot backend services
- `sql/` - Database initialization scripts
- `scripts/` - Deployment and CI/CD scripts

## Setup

### Backend
```sh
cd backend
mvn clean install
mvn spring-boot:run
```

### Deploy with Docker
```sh
cd scripts
docker-compose up -d
```

## Tech Stack

- **Backend**: Spring Boot, MyBatis, Drools, Swagger
- **Database**: MySQL, Redis
- **DevOps**: Docker, Kubernetes, GitLab CI/CD

## License
MIT
