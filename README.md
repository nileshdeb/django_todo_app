# 📝 Django Todo App

A full-featured Todo List web application built with Django. This project was developed for practice to understand Django backend development, project structure, and CRUD functionality.

🔗 **Live Demo:** [django-todo-app](https://django-todo-app-3m40.onrender.com)

---

## 🚀 Features

- ✅ Create, Read, Update, and Delete (CRUD) todo items
- 📋 Clean and intuitive UI built with HTML templates
- 🗄️ Django ORM for database management
- 🔧 Django admin panel support
- ☁️ Deployed on Vercel

---

## 🛠️ Tech Stack

| Layer      | Technology          |
|------------|---------------------|
| Backend    | Python, Django      |
| Frontend   | HTML, CSS           |
| Database   | SQLite (default)    |
| Deployment | Render              |

---

## 📁 Project Structure

```
django_todo_app/
├── todoproject/          # Main Django project directory
│   ├── settings.py       # Project settings
│   ├── urls.py           # Root URL configuration
│   ├── wsgi.py           # WSGI entry point
│   └── ...
├── requirements.txt      # Python dependencies
├── build.sh              # Build script for deployment
└── .gitignore
```

---

## ⚙️ Getting Started

### Prerequisites

- Python 3.8+
- pip

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/nileshdeb/django_todo_app.git
   cd django_todo_app
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate        # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**
   ```bash
   python manage.py migrate
   ```

5. **Run the development server**
   ```bash
   python manage.py runserver
   ```

6. **Open your browser and visit**
   ```
   http://127.0.0.1:8000/
   ```

---

## 🧪 Running Admin Panel

1. Create a superuser:
   ```bash
   python manage.py createsuperuser
   ```

2. Visit `http://127.0.0.1:8000/admin/` and log in with your credentials.

---

## 🚢 Deployment

This app is configured for deployment on **Vercel** using the `build.sh` script.

To deploy manually:

```bash
bash build.sh
```

Make sure your `vercel.json` and environment variables (e.g. `SECRET_KEY`, `DEBUG`, `ALLOWED_HOSTS`) are configured appropriately for production.

---

## 📚 Learning Objectives

This project was built to practice and understand:

- Django project and app structure
- URL routing and views
- Django models and ORM
- Template rendering
- CRUD operations in a web framework
- Deploying a Django app to a hosting platform

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Nilesh Deb**
- GitHub: [@nileshdeb](https://github.com/nileshdeb)
