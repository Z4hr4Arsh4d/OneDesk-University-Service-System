# OneDesk – University Student Service Management System

## Overview

OneDesk is a JavaFX-based desktop application designed to centralize and simplify university student service requests. The system allows students to submit, track, and manage different academic, document, and support-related requests through a single platform.

The project follows an organized layered architecture with separate business logic, database access, and UI modules. It also demonstrates the use of multiple Object-Oriented Programming principles and design patterns.

---

# Features

## Academic Request Management

Students can submit and manage academic-related requests such as:

* Add/Drop Course Requests
* Attendance Correction Requests
* Academic Record Corrections
* Course Registration Issues

## Document Request Services

The system supports document generation and request handling for:

* Transcript Requests
* Enrollment Letter Requests
* ID Card Requests
* Degree Verification Requests

## Student Support Services

Students can also access support-related services including:

* Scholarship Queries
* Fee Support Requests
* Lost & Found Requests
* General Complaints
* Anonymous Complaint Submission

## Admin Dashboard

Administrators can:

* View and process requests
* Monitor request status
* Track audit logs
* Manage request workflows

## Authentication System

* User login system
* Role-based access handling
* Student and admin separation

## Notification & Tracking System

* Request tracking support
* Status updates
* Observer-based notifications

---

# Technologies Used

* Java
* JavaFX
* JDBC
* SQL Server / MySQL
* CSS for JavaFX Styling
* IntelliJ IDEA

---

# Project Structure

```text
src/
│
├── business/
│   ├── academic/
│   ├── admin/
│   ├── document/
│   ├── support/
│   └── shared/
│
├── db/
│   ├── academic/
│   ├── document/
│   └── support/
│
├── database/
│   └── SQL setup scripts
│
├── ui/
│   ├── academic/
│   ├── document/
│   ├── support/
│   └── common/
│
└── Main.java
```

---

# OOP Concepts Used

The project demonstrates multiple Object-Oriented Programming concepts:

* Encapsulation
* Inheritance
* Polymorphism
* Abstraction
* Composition

---

# Design Patterns Implemented

Several software design patterns are used throughout the project:

## Factory Pattern

Used for dynamic request creation.

## Observer Pattern

Used for notifications and status updates.

## Strategy Pattern

Used for eligibility validation and request processing.

## Decorator Pattern

Used for anonymous complaint functionality.

## MVC Architecture

The application follows a Model-View-Controller inspired structure:

* UI Layer
* Business Logic Layer
* Database Layer

---

# Database

The project includes SQL setup and migration scripts:

* `One Desk Setup.sql`
* `Migration_Holds_AndStatuses.sql`

These scripts create the required database schema and tables for the system.

---

# How to Run

## Prerequisites

Make sure the following are installed:

* Java JDK 17 or later
* JavaFX SDK
* SQL Server or MySQL
* IntelliJ IDEA (recommended)

## Steps

1. Clone or extract the project.
2. Open the project in IntelliJ IDEA.
3. Configure the database connection in the DB connection class.
4. Run the SQL setup scripts.
5. Add JavaFX libraries to the project.
6. Run `Main.java`.

---

# Sample Modules

## Academic Module

Handles academic operations such as:

* Add/Drop
* Attendance corrections
* Registration issues

## Document Module

Handles official university documents.

## Support Module

Handles complaints, scholarship queries, and support services.

---

# Future Improvements

Possible future enhancements include:

* Email notifications
* Real-time admin updates
* Mobile application integration
* Cloud database deployment
* File upload support for documents
* Analytics dashboard

---

# Team Contribution

This project was developed as a university project to demonstrate:

* Real-world system design
* Layered architecture
* Database integration
* JavaFX GUI development
* Application of software design patterns

---

# Team Members
* Zahra Arshad
* Rameen Fatima
* Aizah Atif

---

# Screenshots

* Login Screen
<img width="1380" height="958" alt="image" src="https://github.com/user-attachments/assets/e2316910-93f6-461d-9971-2806d7f03d79" />

* Student Dashboard
<img width="1160" height="930" alt="image" src="https://github.com/user-attachments/assets/62a970ad-9c38-4f6a-9339-44aac7293b8c" />

* Admin Dashboard
<img width="1478" height="955" alt="image" src="https://github.com/user-attachments/assets/023f37ff-26c5-432e-ae93-711d39e0f121" />
<img width="1491" height="942" alt="image" src="https://github.com/user-attachments/assets/b3cc8096-3144-41ef-a39b-43604004e314" />


* Request Forms
<img width="1150" height="955" alt="image" src="https://github.com/user-attachments/assets/006b62c7-d44b-49db-8eb1-c13f6712b7b9" />
<img width="1197" height="941" alt="image" src="https://github.com/user-attachments/assets/60d78201-1db8-4594-aa04-3ad3b51972b5" />
<img width="1153" height="936" alt="image" src="https://github.com/user-attachments/assets/b7e72d91-1fa9-41f7-8fbb-e548cf7d4a9d" />
<img width="1172" height="977" alt="image" src="https://github.com/user-attachments/assets/53c70bc6-b8dd-44bc-a01d-c3d1fedb6b50" />





---

# Conclusion

OneDesk provides a centralized and scalable solution for handling university student services efficiently. The system improves request management, reduces manual processing, and demonstrates practical implementation of Java, JavaFX, SQL, and Object-Oriented Design principles.
