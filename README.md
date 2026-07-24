# 🎬 Movie Ticket Booking System

This is a backend project built using **Java** and **Spring Boot** for a movie ticket booking system. The application allows users to browse movies, check available shows, and book tickets. It also includes admin APIs to manage movies, theaters, cities, and shows.

I built this project to improve my understanding of Spring Boot, REST APIs, database design, and how a backend application is structured.

---

## Tech Stack

* Java
* Spring Boot
* Spring Data JPA
* Hibernate
* MySQL
* Maven
* Postman
* Git & GitHub

---

## Features

### User

* Browse movies by city.
* View available shows.
* Check seat availability.
* Book movie tickets.

### Admin

* Add and manage cities.
* Add theaters and screens.
* Add and manage movies.
* Create movie shows.
* Manage seat layouts.

---

## Project Structure

```text
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

## API Endpoints

| Method | Endpoint    | Description        |
| ------ | ----------- | ------------------ |
| GET    | `/movies`   | Get movies by city |
| POST   | `/movies`   | Add a movie        |
| POST   | `/theaters` | Add a theater      |
| POST   | `/shows`    | Create a show      |
| POST   | `/bookings` | Book movie tickets |

---

## What I Learned

Working on this project helped me learn:

* Building REST APIs using Spring Boot.
* Designing database relationships using JPA and Hibernate.
* Organizing a project using Controller, Service, and Repository layers.
* Performing CRUD operations with MySQL.
* Handling exceptions and validating API requests.

---

## Future Improvements

* User Authentication with Spring Security and JWT.
* Online payment integration.
* React frontend.
* Email notifications.
* Docker support.

---

## Author

**Ansul Verma**

Computer Science Student | Java Backend Developer (Learning)
