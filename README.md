# Task Management API

A lightweight RESTful API built with Django, Django REST Framework, and PostgreSQL to manage tasks cleanly and efficiently.

### Tech Stack
* Python
* Django & Django REST Framework
* PostgreSQL
* Psycopg

### Key Features
* Full CRUD endpoints for creating, reading, updating, and deleting tasks
* Structured JSON responses handled by Django REST Framework
* Data persistence powered by a local PostgreSQL database

### How to Set It Up

1. Clone the repository
git clone https://github.com/mohamedabdifatah111/Task-Management-Api.git
cd Task-Management-Api

2. Set up and activate a virtual environment
python -m venv venv
venv\Scripts\activate.bat

3. Install required packages
pip install django djangorestframework psycopg

4. Database Configuration
Update task_manager/settings.py with your local PostgreSQL user, password, and database parameters.

5. Run migrations and start the server
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

6. Test the endpoints
Open http://127.0.0.1:8000/api/tasks/ in your browser to interact with the API interface.