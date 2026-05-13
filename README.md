# Task Manager

A simple to-do app I built with Django. Nothing fancy — just a clean way to manage tasks with login, due dates, and a dashboard to see what's going on.

---

## What it does

- Sign up and log in
- Create, edit, and delete tasks
- Mark tasks as Pending or Completed
- Set due dates (with validation so you can't break things)
- Dashboard that shows your task counts at a glance

---

## Built with

- Python & Django
- SQLite
- HTML, CSS & Bootstrap

---

## Running it locally

```bash
git clone https://github.com/itsmethaj/task-manager.git
cd task-manager

python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

pip install django

python manage.py migrate
python manage.py runserver
```

Then open `http://127.0.0.1:8000` in your browser.

---

## Project structure

```
task-manager/
├── manage.py
├── db.sqlite3
├── tasks/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/
└── requirements.txt
```
