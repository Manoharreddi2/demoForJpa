


# 🎓 Student Management System – Spring Boot + JPA + MySQL

A simple Spring Boot REST API for managing students using Spring Data JPA and MySQL.

## 🚀 Features
- Create a student
- Create multiple students (bulk insert)
- Get all students
- Update student by ID
- Delete student by ID

## 🛠 Tech Stack
- Java
- Spring Boot
- Spring Data JPA
- MySQL
- Hibernate
- Maven
- Postman
- Git & GitHub

## 📂 Project Structure

```
src/main/java/com/example/demoForJpa
├── controller
│   └── StudentController.java
├── entity
│   └── Student.java
├── repo
│   └── StudentRepo.java
└── DemoForJpaApplication.java
```


## 🛠 Tech Stack Used (Detailed)

- **Java** – Core programming language  
- **Spring Boot** – Backend framework for building REST APIs  
- **Spring Data JPA** – ORM layer for database operations  
- **Hibernate** – JPA implementation  
- **MySQL** – Relational database  
- **Maven** – Dependency management & build tool  
- **Postman** – API testing tool  
- **Git & GitHub** – Version control and code hosting  

---

## 🧪 Testing

- APIs tested using **Postman**
- Tested all CRUD operations:
  - Create single student
  - Create multiple students (bulk insert)
  - Fetch all students
  - Update student by ID
  - Delete student by ID
- Verified HTTP status codes:
  - `201 CREATED`
  - `200 OK`
  - `404 NOT FOUND`
- Database operations verified using **MySQL Workbench**
- Tables are automatically created using JPA  
  (`spring.jpa.hibernate.ddl-auto=update`)
