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

  <img width="508" height="442" alt="Screenshot 2026-09-21 201042" src="https://github.com/user-attachments/assets/0ce4bc34-86b3-4f94-930d-d4427d9f2233" />
<img width="449" height="320" alt="Screenshot 2026-09-21 200951" src="https://github.com/user-attachments/assets/e6195457-0000-427c-ac8b-47ab6d84ad3b" />
<img width="447" height="326" alt="Screenshot 2026-09-21 200926" src="https://github.com/user-attachments/assets/2290fc66-991b-4e46-bd67-f1075f4f4348" />
<img width="449" height="252" alt="Screenshot 2026-09-21 201159" src="https://github.com/user-attachments/assets/29022c24-aaaf-44b5-8a5e-5440189cc768" />

