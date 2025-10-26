# fastapi-rest-api-example
Task Manager REST API
# 🧠 Task Manager API (FastAPI + JWT)

A simple **Task Management API** built with **FastAPI**, **SQLAlchemy**, and **JWT authentication**.  
Users can register, log in, and manage their personal tasks securely through token-based access.

---

## 🚀 Features

- ✅ User registration & secure password hashing (bcrypt)
- 🔐 JWT authentication with access tokens
- 📋 CRUD operations for tasks
- 🧱 SQLite database (easily replaceable with PostgreSQL/MySQL)
- 📘 Interactive API docs via Swagger UI (`/docs`)
- ⚙️ Modular structure (separate files for models, schemas, auth, and database)

---

## 🏗️ Project Structure
TaskManager/
│
├── main.py # Main FastAPI app
├── auth.py # JWT and password hashing logic
├── models.py # SQLAlchemy models
├── schemas.py # Pydantic schemas
├── database.py # Database connection setup
├── requirements.txt # Dependencies
└── README.md # Documentation

---

## 💾 Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/taskmanager-api.git
cd taskmanager-api

python -m venv venv
venv\Scripts\activate   # on Windows
# or
source venv/bin/activate   # on Linux/Mac

