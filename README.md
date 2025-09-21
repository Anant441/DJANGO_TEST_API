# 🧪 DJANGO_TEST_API

A beginner-friendly API built with Django for blog management—create, retrieve, update, and delete blog posts with ease.

## 🚀 Features
- CRUD operations for blog posts
- RESTful endpoints
- Django admin integration

## 🛠️ Tech Stack
- Python
- Django
- SQLite (default, can swap for PostgreSQL)

## 📦 Installation
```bash
git clone https://github.com/Anant441/DJANGO_TEST_API.git
cd DJANGO_TEST_API
pip install -r requirements.txt
python manage.py runserver

## 🐳 Run with Docker
```bash
docker build -t django-test-api .
docker run -p 8000:8000 django-test-api
