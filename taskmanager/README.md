# Smart Task Manager

A web app to manage daily tasks with priority levels, deadlines, and status tracking.

## Tech Stack

- **Frontend:** HTML, CSS, Bootstrap 5, JavaScript
- **Backend:** Django (Python)
- **Database:** SQLite

## Features

- User registration and login
- Add, edit, delete tasks
- Priority levels (High, Medium, Low)
- Deadline and status tracking (Pending/Completed)
- Filter tasks by priority and status
- Search tasks by keyword

## Setup Instructions

1. Clone the repo: `git clone https://github.com/anuvind04/smart-task-manager.git`
2. Create virtual environment: `python -m venv venv`
3. Activate: `venv\Scripts\activate`
4. Install Django: `pip install django`
5. Run migrations: `python manage.py migrate`
6. Create superuser: `python manage.py createsuperuser`
7. Run server: `python manage.py runserver`
8. Visit: `http://127.0.0.1:8000`
