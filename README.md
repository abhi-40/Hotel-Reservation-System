# 🏨 Hotel Management System

A simple Java-based Hotel Management System using **JDBC** and **MySQL**.  
This project allows users to perform basic hotel room reservation tasks such as booking, viewing, updating, and deleting reservations.

---

## 📌 Features

- ✅ Reserve a new room
- 📄 View all current reservations
- 🔍 Search room number by reservation ID and guest name
- ✏️ Update existing reservation details
- ❌ Delete a reservation

---

## 💻 Tech Stack

- **Java**
- **MySQL**
- **JDBC (Java Database Connectivity)**

---

## 📁 Database Schema

Database Name: hotel_db  
Table Name: reservations

sql:
CREATE TABLE reservations (
    reservation_id INT PRIMARY KEY AUTO_INCREMENT,
    guest_name VARCHAR(255),
    room_number INT,
    contact_number VARCHAR(15),
    reservation_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);


Update your database credentials in the Java code:

private static final String url = "jdbc:mysql://localhost:3306/database_name";
private static final String Username = "//username";
private static final String password = "//password";
