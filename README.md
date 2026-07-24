# 🎬 Movie Ticket Booking System

A backend application built with **Java** and **Spring Boot** that simulates a real-world movie ticket booking platform. The system allows users to discover movies based on their city, view available shows, and book seats while providing administrators with tools to manage movies, theaters, and show schedules.

The project is designed using a layered architecture and follows RESTful API principles, making it scalable, maintainable, and suitable for learning enterprise backend development.

## 🚀 GitHub Repository

**Repository:** https://github.com/ansul-18/BookMyShow

---

## 🛠 Tech Stack

* **Language:** Java
* **Framework:** Spring Boot
* **Database:** MySQL
* **ORM:** Spring Data JPA, Hibernate
* **Build Tool:** Maven
* **API Testing:** Postman
* **Version Control:** Git & GitHub

---

## ✨ Features

### User Features

* Browse movies based on city.
* View available theaters and show timings.
* Check seat availability.
* Book movie tickets.

### Admin Features

* Manage cities.
* Add and manage theaters.
* Add and manage movies.
* Schedule movie shows.
* Configure seat layouts.

---

## 🏗 Architecture

The project follows a layered architecture:

```
Controller
    ↓
Service
    ↓
Repository
    ↓
MySQL Database
```

This separation improves code maintainability, scalability, and testability.

---

## 📂 Project Structure

```
src/main/java/com/project
│
├── controller
├── service
├── repository
├── entity
├── dto
├── config
└── exception
```

---

## 📡 REST API Endpoints

| Method | Endpoint    | Description             |
| ------ | ----------- | ----------------------- |
| GET    | `/movies`   | Retrieve movies by city |
| POST   | `/movies`   | Add a new movie         |
| POST   | `/theaters` | Add a theater           |
| POST   | `/shows`    | Create a movie show     |
| POST   | `/bookings` | Book movie tickets      |

---

## 📚 Concepts Implemented

* RESTful API Development
* Spring Boot
* Spring Data JPA & Hibernate
* Layered Architecture
* Entity Relationships (One-to-One, One-to-Many, Many-to-Many)
* Exception Handling
* Data Validation
* CRUD Operations
* MySQL Integration

---

## 🔮 Future Enhancements

* JWT Authentication & Spring Security
* Role-Based Access Control (Admin/User)
* Payment Gateway Integration
* React Frontend
* Email Notifications
* Docker Deployment
* Recommendation System

---

## 👨‍💻 Author

**Ansul Verma**

* Java Backend Developer (Learning)
* Passionate about Spring Boot, REST APIs, and Backend Development.
