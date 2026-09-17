# Student Management System

A full-stack Student Management System developed as a CRUD-based web application for managing student records efficiently.

## 📌 Project Overview

The Student Management System allows users to manage student information through Create, Read, Update, and Delete (CRUD) operations.

The project consists of a frontend interface, Django REST Framework backend, and SQLite database.

## 🛠️ Technologies Used

- HTML
- CSS
- JavaScript
- Django
- Django REST Framework
- SQLite
- Git
- GitHub
- Postman

## ✨ Features

- Add new student records
- View student records
- Update student information
- Delete student records
- Unique register number validation
- Email validation
- Django Admin interface
- REST API support
- SQLite database storage
- Responsive frontend interface

## 👨‍🎓 Student Details

The system manages the following information:

- Register Number
- Name
- Department
- Year
- Email
- Phone Number

## 🔗 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/students/` | View all students |
| POST | `/api/students/` | Add a student |
| GET | `/api/students/{id}/` | View a specific student |
| PUT | `/api/students/{id}/` | Update a student |
| DELETE | `/api/students/{id}/` | Delete a student |

## 📂 Project Structure

```text
Student-Management-System/
│
├── backend/
│   ├── config/
│   ├── students/
│   ├── db.sqlite3
│   └── manage.py
│
├── fronted/
│   └── index.html
│
├── .gitignore
└── README.md
