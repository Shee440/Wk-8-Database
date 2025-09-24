# 📚 Library Management System Database

## Overview
This project implements a **Library Management System** using MySQL.  
It manages students, books, librarians, and borrowing records.  

---

## 📂 Database Schema

### 1. Students Table
- Stores the student details.

### 2. Books Table
- Stores and records book details being borrowed.

### 3. Librarians Table
- Records all books borrowed.

### 4. Borrow_Records Table
- Records the borrowed and returned books per the date issued. 

---

## 🔑 Relationships
- **Students → Borrow_Records**: One-to-Many  
- **Books → Borrow_Records**: One-to-Many  
- **Librarians → Borrow_Records**: One-to-Many  

---

## ⚙️ Constraints
- **PRIMARY KEY**: Ensures unique identification of records.  
- **FOREIGN KEY**: Maintains relationships between tables.  
- **UNIQUE**: Ensures no duplicate emails or ISBNs.  
- **NOT NULL**: Required fields cannot be left empty.  

---
