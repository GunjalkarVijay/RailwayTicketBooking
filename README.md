# Railway Ticket Booking System

---

### Description
The Railway Ticket Booking System is a backend-only application built using **Java** and **Spring Boot**. This project is designed to demonstrate the use of core Spring Boot concepts such as annotations, `@RequestMapping`, and validations. The application exposes simple RESTful APIs to perform basic CRUD operations on railway tickets and has been tested using **Postman**.

---

### Table of Contents
1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Prerequisites](#prerequisites)
4. [Usage](#usage)
5. [Contact](#contact)

---

## Features
- **Get All Tickets**: Retrieve a list of all tickets.
- **Get Ticket by PNR**: Retrieve a specific ticket by its PNR (Passenger Name Record).
- **Create New Ticket**: Add a new ticket to the system.
- **Update Ticket**: Update the details of an existing ticket using its PNR.
- **Delete Ticket**: Delete an existing ticket using its PNR.

The project currently stores data in memory using a list and a map, without the use of any database.

---

## Technologies Used
- **Programming Language**: Java
- **Framework**: Spring Boot
- **Build Tool**: Maven 3.0.0
- **IDE**: IntelliJ IDEA / Eclipse
- **Testing**: Postman
- **Validation**: Jakarta Bean Validation

---

## Prerequisites
To run this application locally, ensure you have the following installed:
- Java JDK 8 or higher
- Maven 3.0.0
- IntelliJ IDEA or Eclipse IDE

---

## Usage
1. **Testing with Postman**:
   - Use Postman to interact with the available endpoints.
   - Send requests to perform CRUD operations on the railway tickets.
   - Make sure to send the correct headers and JSON payloads as needed.

2. **Validations**:
   The following validations are applied using `jakarta.validation` and `BindingResult`:
   - **PNR**: Must be greater than 1.
   - **Name**: Length should be between 3 to 20 characters.
   - **Ticket Object**: Contains fields for `pnr`, `name`, `berth`, and `age`.

   The application uses the `@Valid` annotation to ensure that the data provided in the request body meets these criteria.

---

## Contact
For any questions or feedback, feel free to reach out:
- **Email**: vijaygunjalkara54@gmail.com
- **LinkedIn**: [Vijay Gunjalkar](https://www.linkedin.com/in/vijay-gunjalkar-6870a11a9/)

---
