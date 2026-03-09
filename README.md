# Django + React To-Do App

Full-stack To-Do application built with Django (REST API) and React (Vite).

## Features
- Create, update, delete tasks
- REST API with Django
- React frontend with Tailwind CSS
- Separation of backend and frontend

## Tech Stack
- Django
- Django REST Framework
- React + Vite
- Tailwind CSS
- SQLite (dev)

## Setup

### Backend
```bash
cd backend
python -m venv env
source env/bin/activate  # Windows: env\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
