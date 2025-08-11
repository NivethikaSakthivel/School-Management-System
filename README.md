# School Management System

A **Java-based Desktop Application** for managing school operations efficiently with an interactive GUI.  
This system allows you to handle student records, teacher records, marks, and exam details with ease.  
It uses **MySQL Database** for storing and managing all the required data.

---

## 🛠 Tech Stack
- **Java**
- **MySQL**
- **WAMP Server**
- **JDBC**
- **Required JAR files** (links provided below)

---

## 📋 Features / Modules
- **Login / Logout Module**
- **Account Management**
- **Class Management**
- **Subject Management**
- **Exam Management**
- **Student Management**
- **Mark Management**
- **Teacher Management**

---

## 🗂 Database
- MySQL database for all data storage
- Predefined tables for Students, Teachers, Classes, Exams, Subjects, and Marks

---

## 📦 Setup Instructions

### 1️⃣ Prerequisites
- Install **Java JDK**
- Install **NetBeans IDE**
- Install **WAMP Server** (or XAMPP with MySQL)
- MySQL Workbench (optional)

### 2️⃣ Steps to Run the Project
1. Clone or download the project files
2. Open the project in **NetBeans**
3. Import the provided MySQL database file (if available)
4. Update the database connection credentials in the Java code:
   ```java
   String url = "jdbc:mysql://localhost:3306/YOUR_DATABASE_NAME";
   String user = "root";
   String password = "";
