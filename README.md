#  Library Management System

A web-based Library Management System built using Python and Django to manage books, users, and transactions efficiently.

---

##  Features

- Book Management (Add, Update, Delete)
- User Authentication (Login/Register)
- Book Issue & Return System
- Transaction Tracking
- Admin & User Roles
- Secure Data Handling

---

##  Tech Stack

- Backend: Python, Django
- Database: SQLite
- Server: Gunicorn
- Static Files: Whitenoise

---

##  Project Structure

```
librarymanagement/                                                                                                                        
│── manage.py
│── requirements.txt
│── db.sqlite3
│── librarymanagement/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py

---
```

##  Setup Instructions

### 1. Clone the Repository
git clone https://github.com/your-username/library-management-system.git
cd library-management-system

### 2. Create Virtual Environment
python -m venv venv
venv\Scripts\activate

### 3. Install Dependencies
pip install -r requirements.txt

### 4. Run Server
python manage.py runserver

Open: http://127.0.0.1:8000/

---

##  Production Setup

Run using Gunicorn:
gunicorn librarymanagement.wsgi

Static files handled using Whitenoise.

---

##  Architecture

Follows Django MVT pattern:
- Model: Database structure
- View: Business logic
- Template: UI

---

##  Future Improvements

- Email Notifications
- Fine Calculation System
- Cloud Deployment (AWS/Azure)

---

##  Author

ASVPReddy  
Python Full Stack Developer
