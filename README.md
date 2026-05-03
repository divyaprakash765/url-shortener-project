# URL Shortener - Java Full Stack Application

A scalable URL Shortener built using **Spring Boot (Java)** for the backend and a modern frontend (React/Angular). The application allows users to generate short URLs, track analytics, and manage links efficiently.

---

## Features

-  Generate short URLs from long URLs
-  Fast redirection (sub-50ms)
-  Track analytics (click count, timestamps, referrer info)
-  Authentication & Authorization (JWT-based)
-  Role-based access control (RBAC)
-  Smart collision-free URL generation
-  Auto-expiry links using TTL (optional)

---

##  Tech Stack

### Backend
- Java 17
- Spring Boot
- Spring Web (REST APIs)
- Spring Data JPA (Hibernate)
- MySQL / PostgreSQL

### Frontend
- React.js / Angular
- Axios / HTTP Client

### Tools & DevOps
- Git & GitHub
- Postman (API testing)
- Docker (optional)
- Maven / Gradle

---

##  Architecture


- **Controller** → Handles HTTP requests
- **Service** → Business logic (URL generation, validation)
- **Repository** → Database interaction using JPA
- **Database** → Stores original & short URLs

---

##  API Endpoints

### 🔹 Create Short URL