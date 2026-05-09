Task Manager

A minimal to-do list app I built with Django. Nothing fancy — just a clean way to manage tasks with login, status tracking, and a dashboard.

Features

- User signup and login
- Create, edit, delete, and view tasks
- Task status: Pending / Completed
- Due date validation
- Dashboard with task counts

Tech Stack

- Python / Django
- SQLite
- HTML & CSS
- Bootstrap

Getting Started

1. Clone the repo
   git clone https://github.com/itsmethaj/task-manager.git
   cd task-manager

2. Create a virtual environment
   python -m venv .venv
   source .venv/bin/activate
   On Windows: .venv\Scripts\activate

3. Install dependencies
   pip install django

4. Run migrations
   python manage.py migrate

5. Start the server
   python manage.py runserver

6. Open in browser
   http://127.0.0.1:8000

Project Structure

task-manager/
├── manage.py
├── db.sqlite3
├── tasks/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/
└── requirements.txt

Built by Thaj — github.com/itsmethaj
