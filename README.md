# 📚 Library Database Management System (MySQL)

## 📌 Project Description
The **Library Database Management System** is a structured SQL-based project developed using **MySQL** to manage and organize core library operations efficiently.  
This system handles information related to **books, members, employees, branches, and book issuing records** using a relational database approach.

The project focuses on **database design, normalization, relationships, and query execution**, making it suitable for **DBMS / SQL academic projects**.

---

## 🎯 Objectives
- To design a normalized relational database for a library
- To implement table relationships using **primary and foreign keys**
- To perform **CRUD operations** using SQL
- To retrieve meaningful information using **JOINs and queries**
- To understand real-world database modeling

---

## 🛠️ Technologies Used
- **Database:** MySQL  
- **Language:** SQL  
- **Tools:** MySQL Workbench / Command Line

---

## 🗂️ Database Tables
The system consists of the following tables:

- **Branch** – Stores library branch details  
- **Employees** – Stores employee information linked to branches  
- **Members** – Stores registered library members  
- **Books** – Stores book details such as title, author, category, and status  
- **Issued_Status** – Tracks issued books and issue dates  
- **Return_Status** – Tracks returned books and return dates  

---

## 🔗 Database Relationships
- One **branch** can have multiple **employees**
- One **member** can issue multiple **books**
- Each **issued book** is linked to a member and a book
- **Foreign key constraints** maintain data integrity

---

## 📂 Project Structure









---

## 🚀 How to Run the Project

### Step 1: Clone the Repository
```bash
git clone https://github.com/Rishikesh23a/Library-Database-Management-System-MYSQL.git
```
### Step 2: Open MySQL
```
Use MySQL Workbench
```
### Step 3: Create Database & Tables
```
SOURCE schema.sql;
```
### Step 4: Insert Sample Data
```
SOURCE insert_data.sql;
```
### Step 5: Execute Queries
```
SOURCE queries.sql;
```

## 📚 Learning Outcomes

Practical understanding of relational databases

Experience with foreign keys & joins

Hands-on SQL query execution

Real-world database problem modeling
