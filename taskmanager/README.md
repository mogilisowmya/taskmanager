# 📝 Task Manager API (Django REST Framework)

A simple RESTful API built with Django and Django REST Framework (DRF) to manage tasks. It supports basic CRUD operations: Create, Read, Update, and Delete tasks.

---

## 📁 Project Structure

```
taskmanager/
├── manage.py
├── taskmanager/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── tasks/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── serializers.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── db.sqlite3
├── requirements.txt
└── README.md
```

---

## ⚙️ Features

- ✅ Create a new task  
- 📋 View all tasks  
- 🔍 Retrieve a single task  
- ✏️ Update an existing task  
- 🗑️ Delete a task  

---

## 🔧 Tech Stack

- Python 🐍  
- Django 🌐  
- Django REST Framework 🔗  
- SQLite 🗄️  
- Git & GitHub 🧑‍💻  

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/mogilisowmya/taskmanager.git
cd taskmanager
```

### 2. Create a Virtual Environment and Activate

```bash
python -m venv venv
venv\Scripts\activate  # On Windows
# or
source venv/bin/activate  # On Linux/Mac
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Start the Development Server

```bash
python manage.py runserver
```

---

## 📬 API Endpoints

| Method | Endpoint           | Description     |
|--------|--------------------|-----------------|
| GET    | `/api/tasks/`      | List all tasks  |
| POST   | `/api/tasks/`      | Create new task |
| GET    | `/api/tasks/<id>/` | Retrieve task   |
| PUT    | `/api/tasks/<id>/` | Update task     |
| DELETE | `/api/tasks/<id>/` | Delete task     |

---

## 🖼️ Sample Request: Create Task (POST)

```http
POST /api/tasks/
Content-Type: application/json

{
  "title": "Learn Django",
  "description": "Go through Django REST Framework",
  "completed": false
}
```

---

## 👩‍💻 Author

**Sowmya Mogili**  
GitHub: [@mogilisowmya](https://github.com/mogilisowmya)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

