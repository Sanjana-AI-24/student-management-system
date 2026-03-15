# Student Management System

## Project Description
The Student Management System is a full stack web application developed to manage student records efficiently. It allows users to add, view, update, and delete student information through a simple web interface connected to a MySQL database.

This project demonstrates the complete web development process including frontend design, backend development, database integration, API development, and basic authentication.

---

## Technologies Used

Frontend:
- HTML
- CSS
- JavaScript

Backend:
- Node.js
- Express.js

Database:
- MySQL

Development Tools:
- Visual Studio Code
- Git
- GitHub

---

## Features

- Login system
- Add new students
- View student list
- Update student details
- Delete student records
- Responsive dashboard interface
- REST API integration

---

## Project Structure
```
student-management-system
│
├── backend
│ ├── server.js
│ ├── db.js
│
├── frontend
│ ├── login.html
│ ├── index.html
│ ├── script.js
│ ├── style.css
│
├── package.json
└── README.md
```

---



---

## Installation Guide

Step 1: Clone the repository

git clone https://github.com/yourusername/student-management-system.git

Step 2: Navigate to project folder

cd student-management-system

Step 3: Install dependencies

npm install express mysql cors body-parser

Step 4: Start the backend server

node backend/server.js

Step 5: Open the frontend

Open frontend/login.html in your browser.

---

## Database Setup

Create a database in MySQL:

CREATE DATABASE studentdb;

Use the database:

USE studentdb;

Create the students table:

CREATE TABLE students (
id INT AUTO_INCREMENT PRIMARY KEY,
name VARCHAR(100),
email VARCHAR(100),
course VARCHAR(100)
);

---

## System Architecture

Frontend → HTML, CSS, JavaScript  
Backend → Node.js + Express.js  
Database → MySQL

---

## Future Improvements

- User authentication with database
- Search students feature
- Pagination
- Responsive mobile design
- Cloud deployment

---
