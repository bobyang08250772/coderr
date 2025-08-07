
<h1>Coderr</h1>
Coderr is a modern web application designed to make coding offering and ordering easier. It enables users to make offer and order the project according to his needs. 

<h2>Features</h2>

User roles: Guest, User

Providing offers and place orders 

Commenting system for reviewing the providers

Responsive UI for desktop and mobile

Secure backend with Django REST Framework and token-based authentication


<h2>Tech Stack</h2>
Frontend: HTML, CSS, JavaScript

Backend: Django & Django REST Framework

Database: SQLite (for development)

Authentication: Django's built-in user system and token auth

# Coderr Project 

This guide explains how to set up and run an existing Django project using a `requirements.txt` file.

---

## 📦 Prerequisites

- Python 3.13+
- pip installed
- (Optional but recommended) Python virtual environment (`venv`)

---

## 🚀 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/bobyang08250772/coderr.git
```

### 2. Frontend
Notice Frontend and Backend should be runing seperately.
Go to frontend folder, open index.html in Live Server

### 3. Backend

```bash
cd backend
```

### 3.1. Create and Activate a Virtual Environment
```bash
python -m venv venv
```

####  Activate on macOS/Linux
```bash
source venv/bin/activate
```

####  Activate on Windows
```bash
venv\Scripts\activate
```

### 3.2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3.3. Run Migrations
```bash
python manage.py migrate
```

### 3.4. Create a Superuser
```bash
python manage.py createsuperuser
```

### 3.5. Run the Development Server
```bash
python manage.py runserver
```
Open in browser: http://127.0.0.1:8000/





