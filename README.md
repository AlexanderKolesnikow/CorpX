# CorpX: Empowering Startups through a Comprehensive Social Media Application

Repository for the entire project. Uses git submodule to include all other services.

## Description

Corpx is the backend of a Social Media Application meticulously designed to empower startups by facilitating project management, talent acquisition, and financial support alignment with strategic goals and operational necessities.

## 🚀 Features Implemented

Each service with functionalities implemented is equipped with Swagger for easy endpoint testing and exploration.

### [**User Service:**](https://github.com/AlexanderKolesnikow/user_service/tree/master#readme)
- 🌐 [**RecommendationService**](https://github.com/AlexanderKolesnikow/user_service/blob/master/src/main/java/com/kite/kolesnikov/userservice/service/RecommendationService.java)
   - Manages and validates user recommendations within the application.

### [**Project Service:**](https://github.com/AlexanderKolesnikow/project_service/tree/master#readme)
- 📁 [**ProjectResourceService**](https://github.com/AlexanderKolesnikow/project_service/blob/master/src/main/java/com/kite/kolesnikov/projectservice/service/ProjectResourceService.java)
   - Handles CRUD operations of project resources with AWS S3 integration and robust error-handling mechanisms.

## 🛠 Technologies Utilized

- **Programming Language:** 
   - Java
- **Frameworks:**
   - Spring Boot
   - Spring MVC
   - Spring Data
- **Database Management:**
   - Hibernate ORM
   - PostgreSQL
   - Liquibase
- **Containerization:**
   - Docker
- **Version Control:**
   - Git
- **Caching and Message Broker:**
   - Redis
- **Cloud Storage:**
   - AWS S3
   - MinIO
