# Lazarus Project - E-commerce Backend

## Project Overview
This is the backend for an e-commerce store built with Django and Django REST Framework.  
It allows user authentication, product management, and order handling.

## Features (Core)
- User registration & authentication
- Product management (CRUD)
- Order management
- JWT authentication

## Tech Stack
- Django
- Django REST Framework
- Simple JWT
- SQLite (default, can switch to PostgreSQL later)

## Setup Instructions
```bash
git clone <your-repo-link>
cd lazarus_project
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
