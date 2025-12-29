# Subjet_Management_System
# 📘 Subject Management System – Spring Boot CRUD Application

A simple Spring Boot RESTful CRUD application to manage subjects.  
This project demonstrates a clean layered architecture using Controller, Service, Repository, and Entity with an H2 in-memory database.

---

## 🚀 Features

- Create a new subject
- Retrieve all subjects
- Retrieve subject by ID
- Update subject details
- Delete subject
- RESTful APIs
- H2 in-memory database
- MVC-based clean architecture

---

## 🛠️ Tech Stack

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- H2 Database
- Maven

---

## 📂 Project Structure

src/main/java  
│  
├── controller  
│   └── SubjectController.java  
│  
├── service  
│   └── SubjectService.java  
│  
├── repository  
│   └── SubjectRepository.java  
│  
├── model  
│   └── Subject.java  
│  
└── SubjectManagementApplication.java  

---

## ⚙️ Configuration

- Server Port: 8081
- Database: H2 (In-memory)
- Hibernate DDL Auto: update
- H2 Console Enabled

---

## ▶️ How to Run the Application

1. Clone the repository
   git clone <your-repository-url>

2. Open the project in IntelliJ IDEA / Eclipse

3. Run the main class:
   SubjectManagementApplication.java

4. Application will start on:
   http://localhost:8081

---

## 🔗 API Endpoints

### ➕ Create Subject
POST /subjects

Request Body:
{
  "name": "Mathematics",
  "code": "MATH101"
}

---

### 📥 Get All Subjects
GET /subjects

---

### 📥 Get Subject by ID
GET /subjects/{id}

---

### ✏️ Update Subject
PUT /subjects/{id}

Request Body:
{
  "name": "Advanced Mathematics",
  "code": "MATH201"
}

---

### ❌ Delete Subject
DELETE /subjects/{id}

---

## 🧪 H2 Database Console

URL:
http://localhost:8081/h2-console

JDBC URL:
jdbc:h2:mem:testdb

Username: sa  
Password: (leave blank)

---

## 🎯 Learning Outcomes

- Spring Boot REST API development
- Layered architecture implementation
- JPA and Hibernate integration
- CRUD operations
- In-memory database usage

---

## 👨‍💻 Author

Manav Mishra  
Student 
