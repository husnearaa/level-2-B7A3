# ⚽ Football Ticket Booking System

This repository contains the solution for the **Football Ticket Booking System** database assignment. The project focuses on designing a relational database, creating an Entity Relationship Diagram (ERD), and writing SQL queries to retrieve and manage football ticket booking data.

## 📌 Project Overview

The system manages:

- Users (Football Fans and Ticket Managers)
- Football Matches
- Ticket Bookings

It demonstrates database design concepts including primary keys, foreign keys, relationships, constraints, and SQL query writing.

---

## 📂 Project Contents

### Part 1: ERD Design

- Designed an Entity Relationship Diagram (ERD)
- Included the following tables:
  - Users
  - Matches
  - Bookings
- Implemented:
  - Primary Keys (PK)
  - Foreign Keys (FK)
  - One-to-Many relationship (Users → Bookings)
  - Many-to-One relationship (Bookings → Matches)
  - Logical One-to-One mapping for each booking record
  - Crow's Foot notation

---

### Part 2: SQL Implementation

Implemented:

- Table creation with appropriate data types
- Primary Key constraints
- Foreign Key constraints
- UNIQUE constraint
- CHECK constraints
- Sample data insertion
- SQL queries using:
  - WHERE
  - ILIKE
  - COALESCE
  - IS NULL
  - INNER JOIN
  - LEFT JOIN
  - Subqueries
  - Aggregate Functions (AVG)
  - ORDER BY
  - LIMIT & OFFSET

---

## 🗂 Database Tables

- Users
- Matches
- Bookings

---

## 📋 SQL Queries

The project includes solutions for the following queries:

1. Retrieve available Champions League matches.
2. Search users by name using pattern matching.
3. Replace NULL payment status using `COALESCE`.
4. Display booking details using `INNER JOIN`.
5. Display all users including those without bookings using `LEFT JOIN`.
6. Find bookings with a total cost greater than the average booking cost.
7. Retrieve the top 2 most expensive matches after skipping the highest-priced match.

---

## 🛠 Technologies Used

- PostgreSQL
- SQL
- Draw.io (ERD)

---

## 📁 Repository Structure

```
.
├── QUERY.sql
└── README.md
```

