# 📚 Django REST API – Book CRUD

A simple RESTful API built using **Django** and **Django Rest Framework (DRF)** that provides full CRUD functionality (Create, Read, Update, Delete) for managing books.

---

## 🚀 Features

- ✅ Create a book (POST)
- ✅ Retrieve all books (GET)
- ✅ Retrieve a single book by ID (GET)
- ✅ Update a book (PUT)
- ✅ Delete a book (DELETE)
- ✅ JSON-based REST API
- ✅ Clean and structured project layout

---

## 🛠 Tech Stack

- Python 3.x
- Django
- Django Rest Framework
- SQLite (default database)

---


## ⚙️ Installation & Setup

### 1. Clone the repository

```
git clone https://github.com/Ishanhirani11/REST-API-Using-DRF.git
cd REST-API-Using-DRF
```

### 2. Create virtual environment

```
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

### 4. Run migrations

```
python manage.py makemigrations
python manage.py migrate
```

### 5. Start the server

```
python manage.py runserver
```

Visit:

```
http://127.0.0.1:8000
```

## 📌 API Endpoints

Base URL:

http://127.0.0.1:8000/api/


| Method | Endpoint | Description |
|--------|----------|------------|
| GET | `/api/books/` | Get all books |
| POST | `/api/books/` | Create a new book |
| GET | `/api/books/<id>/` | Get single book |
| PUT | `/api/books/<id>/` | Update book |
| DELETE | `/api/books/<id>/` | Delete book |

---

## 🧪 Sample Request Body (POST / PUT)

```json
{
  "title": "Django for Beginners",
  "author": "William S. Vincent",
  "price": 39.99
}