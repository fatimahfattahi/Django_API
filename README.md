# Book Review API

A Django REST Framework project for managing book reviews with JWT authentication.

## Features

- User registration and login
- token-based authentication
- List and retrieve book details
- Admins can add, update, delete books
- Users can add, edit, delete their own reviews
- Password change functionality
- Permissions and error handling

---

## Tech Stack

- Python 3
- Django 4+
- Django REST Framework
- djangorestframework-simplejwt
- SQLite3 (default database)

---

## Installation

```bash
git clone https://github.com/your-username/book-review-api.git
cd book-review-api
python -m venv env
source env/bin/activate  # Windows: env\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
