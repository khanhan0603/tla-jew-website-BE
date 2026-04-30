# Jewelry Management System (Backend)

Backend system for managing products and orders in an online jewelry platform.

---

## Tech Stack

* Java 21
* Spring Boot
* Spring Data JPA
* MySQL
* Maven
* GitHub Actions (CI)

---

## Features

* JWT Authentication (Admin / User)
* Product & Category Management
* Order Processing
* User Management
* Layered Architecture (Controller → Service → Repository)

---

## Database

Relational database design with MySQL.

---

## Run Project

```bash
mvn clean install
mvn spring-boot:run
```

---

## Configuration

Edit `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/tla_jew
spring.datasource.username=root
spring.datasource.password=your_password
```

---
## Default Account

On the first run, the system automatically initializes a default admin account:

* **Username:** `admin`
* **Password:** `admin`

> For security reasons, please change the default credentials after the first login.

---
## CI/CD

* GitHub Actions for automated build and validation

---
