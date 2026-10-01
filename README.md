# Django Jazzmin Project

A web application developed with **Django**, using **Jazzmin** to customize and enhance the Django administration interface.

This project is being developed as part of my studies and practical learning with Django, covering the main concepts and features presented throughout the course.

## 🚀 Technologies

* Python
* Django
* Django Jazzmin
* SQLite
* HTML
* CSS
* Git & GitHub

## 📚 Project Goals

The main goal of this project is to practice and apply Django concepts in a real application, including:

* Django project and application structure
* Models and database management
* Migrations
* Django Admin
* Custom Admin configurations
* Forms and data validation
* URLs and views
* Templates
* Static files
* Database relationships
* CRUD operations
* Authentication and user management
* Administration interface customization with Jazzmin

## 📁 Project Structure

```text
django-jazzmin-project/
│
├── app/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
│
├── project/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── .gitignore
├── manage.py
├── README.md
└── requirements.txt
```

> The project structure may change as new features and applications are added.

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/w11k3/django-jazzmin-project.git
```

### 2. Enter the project directory

```bash
cd django-jazzmin-project
```

### 3. Create a virtual environment

```bash
py -m venv .venv
```

### 4. Activate the virtual environment

On Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

### 5. Install the dependencies

```bash
pip install -r requirements.txt
```

### 6. Apply the migrations

```bash
py manage.py migrate
```

### 7. Run the development server

```bash
py manage.py runserver
```

The application will be available at:

```text
http://127.0.0.1:8000/
```

## 🔐 Django Admin

To create an administrator account:

```bash
py manage.py createsuperuser
```

After creating the account, access:

```text
http://127.0.0.1:8000/admin/
```

The administration interface is customized using **Jazzmin**.

## 🛠️ Development

This project is continuously evolving as new Django concepts are studied and implemented.

New features, improvements, models, and applications will be added throughout the development process.

## 👨‍💻 Author

**Willian Kauê da Cruz Campos**

Software Engineering student focused on backend development and continuous learning.

---

⭐ This project is part of my journey learning and practicing Django.
