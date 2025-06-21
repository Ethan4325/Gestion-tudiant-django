# 🎓 Student Management - Django Project

A simple yet functional student management system built with Django — the powerful Python web framework. Manage student data efficiently with a clean web interface and admin panel! 🚀

## ✨ Features

Add, update, and delete student records easily.
Django Admin for super-user management.
Clean project structure following Django best practices.
Ready to expand with user authentication, course management, and more!
![304469461-11e5554c-cbd4-4252-9430-96776d1c4b6e](https://github.com/Ethan4325/Gestion-tudiant-django/assets/156784806/0ff7b51f-3bf1-404f-901e-ef0bbbe8c0de)

### 🛠️ Installation & Setup

Clone the repository:
git clone https://github.com/Ethan4325/Gestion-tudiant-django.git
cd Gestion-tudiant-django
Create and activate a virtual environment (recommended):
python -m venv venv
#### On Windows
venv\Scripts\activate
#### On macOS/Linux
source venv/bin/activate
Install dependencies:
pip install -r requirements.txt
(If you don’t have a requirements.txt file, install Django manually:)

pip install django
Apply migrations:
python manage.py migrate
Create a superuser to access the Django admin:
python manage.py createsuperuser
Run the development server:
python manage.py runserver
Open your browser and go to:
http://127.0.0.1:8000/
Access the admin panel:
http://127.0.0.1:8000/admin
Log in with your superuser credentials to manage students and other data.

#### 🚀 How to Use

Use the web interface or the Django admin panel to manage student information.
The project can be extended easily for features like course enrollment, grades, attendance, and more.
#### 📁 Project Structure

Gestion-tudiant-django/
│
├── manage.py              # Django administrative utility
├── FirstProject/          # Main Django project folder (settings, urls, wsgi)
├── students/              # Django app managing student data
├── db.sqlite3             # Default SQLite database (auto-generated)
└── requirements.txt       # Python dependencies
#### 📝 Notes

Make sure your Python environment is correctly set up.
Activate your virtual environment before running commands.
Customize the settings.py if you want to use another database like PostgreSQL or MySQL.
