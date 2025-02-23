```md
# Pinda TMS - Transport Management System (Java Backend)

Pinda TMS is a cloud-native **Transport Management System (TMS)** built using **Spring Boot**, designed for **order management (OMS)** and **user management** in logistics and transportation.

## Project Structure

- `backend/` - Java Spring Boot microservices:
  - `pd-oms/` - Order Management System (OMS)
  - `pd-user/` - User Management System
- `sql/` - Database initialization scripts
- `scripts/` - Deployment and CI/CD scripts

## Key Features

### **1. Order Management System (OMS)**
- Handles **order creation, cargo tracking, and order processing**.
- Uses **MyBatis** for database operations.
- Integrated with **Drools Rule Engine** for business logic automation.
- Provides **RESTful APIs** documented with **Swagger**.

### **2. User Management System**
- Manages **users, authentication, and address books**.
- Uses **Redis** for caching user sessions and speeding up queries.

### **3. High-Performance & Scalable Architecture**
- **Spring Boot** microservices architecture.
- **Redis** for caching and high-speed data access.
- **MySQL** as the primary relational database.
- **Docker & Kubernetes** for scalable deployments.
- CI/CD pipeline using **GitLab CI/CD**.

## Setup & Deployment

### **1. Running the Backend**
```sh
cd backend
mvn clean install
mvn spring-boot:run
```

### **2. Running with Docker**
```sh
cd scripts
docker-compose up -d
```

### **3. Kubernetes Deployment**
```sh
kubectl apply -f k8s/
```

## Tech Stack

- **Backend**: Spring Boot, MyBatis, Drools, Swagger
- **Database**: MySQL, Redis
- **DevOps**: Docker, Kubernetes, GitLab CI/CD

## License
MIT
```

