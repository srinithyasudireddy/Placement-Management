# Placement Management System

## Project Overview

The **Placement Management System** is a web-based application designed to streamline the placement process for colleges. It allows students to register, apply for jobs, and track placement progress, while companies can post job openings and manage candidate applications. The system is built using **Java**, **Spring Boot**, **Spring MVC**, and utilizes **PostgreSQL** and **MySQL** for database management.

## Technologies Used

- **Backend:**
  - Java
  - Spring Boot
  - Spring MVC
  - JDBC

- **Database:**
  - PostgreSQL
  - MySQL

- **Tools:**
  - Maven (for dependency management)
  - IntelliJ IDEA (IDE)
  - Postman (API testing)

## Features

- **Student Module:**
  - Registration and login for students.
  - View available job postings from companies.
  - Apply for jobs and track application status.

- **Company Module:**
  - Register and manage company profile.
  - Post job openings.
  - Manage student applications for job postings.

- **Admin Module:**
  - Manage student and company data.
  - Track placement statistics and reports.

## Database Integration

- Integrated both **PostgreSQL** and **MySQL** databases for storing different types of data:
  - **PostgreSQL** is used for storing student data.
  - **MySQL** is used for storing company and job posting data.

- Employed **JDBC** for seamless database connectivity, handling CRUD operations for both student and company modules.

## Key Features Implemented

- **Spring Boot & Spring MVC Integration:**
  - Designed and implemented the core business logic using **Spring Boot**.
  - Implemented **Spring MVC** architecture for a clear separation of concerns in the web application.

- **CRUD Operations:**
  - Created and implemented database connectivity using **JDBC** for efficient CRUD operations (Create, Read, Update, Delete) for both students and companies.

- **Job Application System:**
  - Students can apply for jobs listed by companies.
  - Companies can view and manage student applications for posted job openings.

## Setup Instructions

1. **Clone the repository:**
   ```bash
   [git clone <repository_url>](https://github.com/srinithyasudireddy/Placement-Management.git)
   ```
2. **Install dependencies:**

Ensure you have Java and Maven installed on your system.

3. **Configure database:**

Set up PostgreSQL and MySQL databases as per the configuration files (application.properties or application.yml).

4. **Run the application:**x`

Use the following command to run the Spring Boot application:

```bash
mvn spring-boot:run
```
5. **Additional Information**
   
This project is designed with scalability and ease of maintenance in mind, ensuring that both student and company modules work efficiently within the broader context of college placements. Feedback and contributions are welcome to help enhance the system further.


