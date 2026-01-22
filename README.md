# 📝 FastAPI To-Do List App

A simple and clean To-Do List web application built with **FastAPI**, **SQLAlchemy**, and **Jinja2**, featuring user authentication and task management.

This project was built to get hands-on experience with FastAPI, backend development, and basic authentication flows.

---

## 🚀 Features

- User Registration and Login
- Secure Password Hashing (bcrypt)
- Add, Update, Delete Tasks
- Mark Tasks as Completed
- Cookie-based Authentication
- Server-rendered HTML using Jinja2 templates

---

## 🛠 Tech Stack

- **Backend Framework:** FastAPI  
- **ORM:** SQLAlchemy  
- **Database:** SQLite  
- **Templating Engine:** Jinja2  
- **Authentication:** Passlib (bcrypt)  
- **Server:** Uvicorn  

---

## 📁 Project Structure
To-Do-List/

│

├── templates/ # HTML templates

├── app.py # Main FastAPI application

├── models.py # Database models

├── database.py # Database configuration

├── .gitignore

└── README.md



---

## ⚡ Getting Started

Follow these steps to run the project locally.

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Anshita0310/To-Do-List.git
cd To-Do-List
```

### 2️⃣ Create and activate a virtual environment

Windows (PowerShell):
```
python -m venv .venv
.\.venv\Scripts\activate
```
macOS / Linux:
```
python3 -m venv .venv
source .venv/bin/activate
```
### 3️⃣ Install dependencies
```
pip install fastapi uvicorn sqlalchemy jinja2 passlib[bcrypt]
```
### 4️⃣ Run the application
```
uvicorn app:app --reload
```
Open your browser and visit:
👉 http://127.0.0.1:8000

### 🔐 Authentication

- Passwords are securely hashed using bcrypt

- Authentication is handled via HTTP cookies

- Unauthorized users are redirected to the login page

### 📌 Notes

- Uses SQLite for simplicity

- Database file is created automatically

- Ideal for learning FastAPI fundamentals

- Not intended for production use without improvements

### 🌱 Possible Enhancements

- Add due dates and priorities

- Task filtering (completed / pending)

- User profile page

- JWT-based authentication

- Deploy on Render / Railway

- Convert frontend to React
