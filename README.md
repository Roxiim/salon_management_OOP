# Enterprise Salon Management Platform

A multi-tier Java desktop application engineered for secure, concurrent scheduling and user management. The system architecture enforces strict separation of concerns utilizing the MVC design pattern, coupled with a robust PostgreSQL data persistence layer.

## 🚀 System Architecture & Patterns
- **MVC (Model-View-Controller):** Complete decoupling of the JavaFX graphical interface from the core business logic.
- **DAO (Data Access Object) & Factory:** Centralized database connection management ensuring optimized, leak-free PostgreSQL connections.
- **Role-Based Access Control (RBAC):** Distinct workflows, specific UI renderings, and permission levels for Administrators, Stylists, and Clients.

## 🛡️ Security & Data Integrity
- **Cryptographic Hashing:** User passwords are encrypted prior to database insertion, neutralizing plain-text vulnerabilities.
- **Conflict-Resolving Engine:** Algorithmic validation of appointment time-slots to guarantee 100% relational data integrity and prevent overlapping bookings.
- **Prepared Statements:** Complete mitigation of SQL Injection vectors across all CRUD operations via parameterized JDBC queries.

## 💻 Tech Stack
- **Language:** Java (JDK 17+)
- **GUI Framework:** JavaFX
- **Database:** PostgreSQL
- **Database Connectivity:** JDBC
