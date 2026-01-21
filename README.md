# Employee Task Management System

A backend-driven application built using **FastAPI** to manage employees, assign tasks, track task status, and log issues efficiently.

---

## 📌 Project Overview

The Employee Task Management System is designed to provide a centralized platform for managing employees and their assigned tasks.  
It focuses on backend development concepts such as REST APIs, database integration, and modular architecture.

The system supports:
- Employee management
- Task assignment and status tracking
- Issue logging for tasks
- API testing using Swagger
- Command Line Interface (CLI) operations

---

## 🛠️ Technologies Used

- **Programming Language:** Python  
- **Backend Framework:** FastAPI  
- **Database:** SQLite  
- **ORM:** SQLAlchemy  
- **API Documentation:** Swagger UI  
- **Version Control:** Git & GitHub  

---

## 📂 Project Structure




employee-task-manager/
│
├── app/                     # Main backend application
│   ├── __init__.py
│   ├── main.py              # FastAPI app entry point
│   ├── database.py          # Database connection (SQLite)
│   ├── models.py            # Database models (tables)
│   ├── schemas.py           # Pydantic schemas (request/response)
│   └── routes/              # API route modules
│       ├── __init__.py
│       ├── employee.py      # Employee APIs
│       ├── task.py          # Task APIs
│       └── issue.py         # Issue logging APIs
│
├── cli/                     # Command Line Interface
│   ├── __init__.py
│   └── cli.py               # CLI commands for employees/tasks
│
├── frontend/                # Simple frontend (optional)
│   └── index.html
│
├── tests/                   # Test cases (optional)
│
├── requirements.txt         # Project dependencies
├── .gitignore               # Ignored files (venv, db, cache)
├── README.md                # Project documentation
└── employee.db              # SQLite database (ignored by git)


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/aravindroy1/employee-task-manager.git
cd employee-task-manager

2️⃣ Create Virtual Environment

python -m venv venv

Activate it:

Windows
venv\Scripts\activate

3️⃣ Install Dependencies

pip install -r requirements.txt

▶️ Running the Application

Start the FastAPI Server
uvicorn app.main:app --reload

Server will run at:http://127.0.0.1:8000

📘 Swagger API Documentation

http://127.0.0.1:8000/docs

You can:

Add employees

Create and update tasks

Log issues

View all records

💻 Command Line Interface (CLI)
Run CLI using: python cli/cli.py

CLI allows:

Adding employees

Viewing employee data

Interacting with backend logic via terminal

🧪 Testing
APIs tested using Swagger UI

CLI tested via terminal commands

Database records verified using API responses

🔒 Git Ignore Configuration
The following files are ignored:

venv/

employee.db

__pycache__/

.env

This ensures only source code is tracked.

🚀 Future Enhancements
User authentication and authorization

Role-based access control

Advanced frontend using React

Cloud database integration

Dashboard and analytics

👨‍💻 Team Members
Aravind 

Thanusri Karuturi

✅ Conclusion
This project demonstrates practical backend development skills using FastAPI, REST APIs, and database integration, making it suitable for academic and real-world applications.


📎 License
This project is for educational purposes.


---

# 🚀 HOW TO UPDATE README ON GITHUB

After saving `README.md`, run these commands in VS Code terminal:

```bash
git add README.md
git commit -m "Update README with project details"
git push origin master

(or main if your branch is main)





