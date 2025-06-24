# 📚 Library SQL Project

This is a simple Library Management System built using MySQL. It includes the database schema, table relationships, and an ER diagram to illustrate the design.

---

## 🧱 Tables Included

1. **Students**
   - StudentID (PK)
   - Name
   - Email
   - Branch

2. **Authors**
   - AuthorID (PK)
   - Name
   - Country

3. **Books**
   - BookID (PK)
   - Title
   - Genre
   - AuthorID (FK to Authors)

4. **IssueRecords**
   - IssueID (PK)
   - BookID (FK to Books)
   - StudentID (FK to Students)
   - IssueDate
   - ReturnDate

---

## 🗃️ Files Included

- `schema.sql` – SQL script to create all tables and relationships
- `Library_ER_Diagram.png` – ER diagram for the database schema
- `Library_SQL_Project.zip` – ZIP file with all resources

---

## ✅ Features

- Clean and normalized schema
- Includes foreign keys to ensure relational integrity
- Easy to expand and integrate into web apps or projects

---

## 🛠️ How to Run

1. Open `schema.sql` in MySQL Workbench
2. Run the script to create the database and tables
3. Use `SELECT * FROM table_name;` to verify table creation
4. Use sample `INSERT` queries to test data

---

> Created as part of SQL learning / academic project.