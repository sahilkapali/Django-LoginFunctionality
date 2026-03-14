# Django-LoginFunctionality

A simple authentication system built with **Django** that provides a user login interface and integrates with Django's authentication framework. This project demonstrates how to implement a basic login workflow using a dedicated `accounts` app.

---

## 📌 Features

* User login using Django authentication
* Custom login form
* Template-based login page
* Organized Django app structure
* Admin panel integration
* Secure password handling
* SQLite database for development

---

## 🛠️ Tech Stack

* **Backend:** Django (Python)
* **Frontend:** HTML / CSS (Django Templates)
* **Database:** SQLite
* **Authentication:** Django Built-in Auth System

---

## 📂 Project Structure

```
djangologin/
│
├── myproject/
│   │
│   ├── accounts/                # Authentication app
│   │   ├── migrations/
│   │   ├── templates/accounts/  # Login templates
│   │   ├── __init__.py
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── forms.py
│   │   ├── models.py
│   │   ├── tests.py
│   │   ├── urls.py
│   │   └── views.py
│   │
│   ├── myproject/               # Project configuration
│   │   ├── __init__.py
│   │   ├── asgi.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   │
│   ├── db.sqlite3               # Development database
│   └── manage.py                # Django management script
│
├── venv/                        # Virtual environment
├── LICENSE
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/django-login-system.git
cd django-login-system
```

---

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

---

### 3️⃣ Activate Virtual Environment

**Windows**

```
venv\Scripts\activate
```

**Mac/Linux**

```
source venv/bin/activate
```

---

### 4️⃣ Install Dependencies

```
pip install django
```

or

```
pip install -r requirements.txt
```

---

### 5️⃣ Apply Migrations

```
python manage.py migrate
```

---

### 6️⃣ Create Admin User

```
python manage.py createsuperuser
```

Follow the prompts to create a username and password.

---

### 7️⃣ Run the Development Server

```
python manage.py runserver
```

---

## 🌐 Access the Application

Open your browser and go to:

```
http://127.0.0.1:8000/
```

Admin Panel:

```
http://127.0.0.1:8000/admin/
```

---

## 🔐 Authentication Flow

1. User opens login page
2. Enters username and password
3. Form is validated using Django forms
4. Django authentication system verifies credentials
5. User is redirected after successful login

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 👨‍💻 Author

Developed as a learning project for implementing authentication in Django.
