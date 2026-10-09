# Job Application Tracker

A web-based application built with Java and Spring Boot to help users organize and track their job applications in one place.

## 📌 About the Project

The Job Application Tracker helps users maintain records of their job applications, monitor application statuses, and view an overview of their job search progress.

This project was developed to gain hands-on experience with Java, Spring Boot, database integration, and server-side web development.

## ✨ Features

* **Add Applications:** Save job details, including company name, job role, application date, status, and location.
* **View Applications:** Display saved job applications in a structured table.
* **Update Applications:** Edit existing application details.
* **Delete Applications:** Remove application records when needed.
* **Search Applications:** Search by company name, job role, or application status.
* **Dashboard:** View application counts and status-wise statistics.
* **Statistics and Reports:** Planned enhancements include a report page and visual charts.

## 🛠️ Technologies Used

| Technology      | Purpose                                     |
| --------------- | ------------------------------------------- |
| Java            | Backend programming                         |
| Spring Boot     | Application setup and configuration         |
| Spring MVC      | Handling HTTP requests and controller logic |
| Spring Data JPA | Database access and repository operations   |
| Hibernate       | Object-relational mapping implementation    |
| MySQL           | Storing job application records             |
| Thymeleaf       | Rendering dynamic HTML pages                |
| HTML            | Structuring web pages                       |
| CSS             | Styling and layout                          |
| Maven           | Dependency management and project build     |
| IntelliJ IDEA   | Development environment                     |

## 🏗️ Project Architecture

The application follows a layered architecture:

```text
User / Browser
      ↓
HTML + CSS + Thymeleaf
      ↓
Controller Layer
      ↓
Service Layer
      ↓
Repository Layer
      ↓
JPA / Hibernate
      ↓
MySQL Database
```

### Main Components

* **Entity:** Represents job application data mapped to a database table.
* **Controller:** Handles browser requests and selects the appropriate view.
* **Service:** Contains application logic and coordinates operations.
* **Repository:** Provides database operations through Spring Data JPA.
* **Thymeleaf Templates:** Display dynamic application data.

## 🗂️ Project Structure

```text
Job-Application-Tracker/
├── src/
│   └── main/
│       ├── java/
│       │   └── .../
│       │       ├── entity/
│       │       ├── repository/
│       │       ├── service/
│       │       └── controller/
│       └── resources/
│           ├── templates/
│           │   ├── index.html
│           │   ├── add-job.html
│           │   └── statistics.html
│           ├── static/
│           │   └── css/
│           │       └── style.css
│           └── application.properties
├── pom.xml
└── README.md
```

*The structure above is illustrative; adjust filenames to match the current repository.*

## ⚙️ How to Run Locally

### Prerequisites

* Java JDK compatible with the project
* IntelliJ IDEA or another Java IDE
* MySQL Server
* Maven

### Steps

1. Clone or download this repository.
2. Open the project in IntelliJ IDEA.
3. Create a MySQL database for the application.
4. Configure the database URL, username, and password in `application.properties`.
5. Allow Maven to download the project dependencies.
6. Run `JobApplicationTrackerApplication.java`.
7. Open your browser and visit:

   `http://localhost:8081/`



## 🎯 Learning Outcomes

Through this project, I gained practical experience with:

* Building a web application using Spring Boot.
* Understanding the Model-View-Controller (MVC) pattern.
* Separating controller, service, and repository responsibilities.
* Performing CRUD operations using Spring Data JPA.
* Mapping Java entities to a MySQL database.
* Creating dynamic web pages with Thymeleaf.
* Implementing search and dashboard functionality.

## 🚀 Future Enhancements

* Interactive charts and detailed application analytics.
* Improved form validation and error handling.
* User authentication and authorization.
* Pagination and date-based filtering.
* Automated unit and integration testing.






