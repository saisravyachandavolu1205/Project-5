# Project-5
Library Management System – SQL Project
This project implements a Library Management System using SQL to manage and streamline book cataloging, membership, borrowing, and overdue tracking processes. Designed as a robust backend database solution, the system supports core library operations efficiently and can be extended to support public, school, or university libraries.

**Project Objectives**
Build a relational database for a library
Handle book inventory, borrowers, loan tracking, and overdue alerts
Implement queries for real-time insights like book availability and most borrowed titles
Enforce data integrity and normalization using SQL constraints

**Database Design**
The system consists of multiple normalized tables:
Books: Stores book details including title, author, genre, and publisher
Members: Tracks registered library users
Borrow: Manages borrowing and return activity
Genre: Categorizes books for filtered search
Overdue: Identifies and flags late returns
All tables use primary keys, foreign keys, and appropriate data types to ensure consistency and scalability.

**Key Features**
Add, update, or delete books and members
Check material availability in real time
Track borrow/return history per user
Automatically identify overdue books
View most borrowed books and user borrowing frequency
Organize and filter books by genre

**Technologies Used**
MySQL (via MySQL Workbench / phpMyAdmin / CLI)
SQL DDL: CREATE, ALTER, DROP
SQL DML: INSERT, UPDATE, DELETE
SQL Queries: JOIN, GROUP BY, ORDER BY, subqueries, date functions

 **Sample Queries Included**
List of overdue books
Most borrowed books
Top members by borrowing frequency
Books by genre and availability
Due date tracking with alerts

 **Highlights**
Follows third normal form (3NF) to avoid redundancy
Ensures referential integrity between borrowers and borrowed books
Uses constraints for data validation and accuracy

Designed for ease of integration with future UI (e.g., Java/Python front-end)

