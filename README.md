# SISTEM-KAFE-SIBER

# SQL Database Practice & Architecture

Welcome to my SQL portfolio. This repository contains my database design projects and query practices as I build my foundation in software engineering and data management.

## 🗄️ Project 1: Cyber Cafe Management System

A relational database built to manage a cyber cafe's operations, tracking customers, computer hardware specs, and gaming session logs.

### 📊 Database Schema
The system is built on a 3-table architecture using **Primary Keys** and **Foreign Keys** to maintain relational integrity.
- **Customer**: Stores customer details (ID, Name, Membership Type).
- **Computer**: Stores hardware details (ID, Specs, Hourly Rate).
- **SessionLog**: The bridge table linking customers to the computers they used, recording session dates and hours played.

### 🛠️ Skills Demonstrated
- **Database Design (DDL):** Creating tables with proper constraints (`PRIMARY KEY`, `FOREIGN KEY`, `NOT NULL`).
- **Data Manipulation (DML):** Inserting structured records into related tables.
- **Relational Querying (JOINs):** 
  - Understanding how Foreign Keys act as "bridges" between tables.
  - Writing 2-Table Joins.
  - Writing 3-Table (Triple) Joins to retrieve data across the entire system.
- **Data Filtering:** Combining `JOIN` logic with `WHERE`, `AND`, `OR`, `BETWEEN`, and `ORDER BY` clauses to generate specific reports.

### 📁 Files Included
- `setup_database.sql`: Contains the database creation, schema (tables), and initial dummy data.
- `joins_practice.sql`: Contains a collection of queries demonstrating 2-table and 3-table JOIN logic with filters.
- `er_diagram.png`: A visual representation of the database relationships (Foreign Keys).

---
*Created as part of my ongoing journey in database architecture and backend logic.*
