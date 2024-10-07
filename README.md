# Simple To-Do List App

## Overview
The Simple To-Do List App is a straightforward application designed to help you manage your daily tasks efficiently. It allows you to add, edit, and delete tasks with ease.

## Features
# Project Overview
Key Features:
User Authentication (Sign up, Login, Logout).
CRUD for To-Do Tasks:
Create: Add a new task.
Read: View tasks.
Update: Mark tasks as done/undone or edit the task.
Delete: Remove tasks.
Task categories (optional feature, e.g., Work, Personal).
Task deadlines and priorities (optional feature).
Tech Stack:
Backend: Flask.
Database: SQLite.
Frontend: HTML, CSS (with Bootstrap or any simple framework for styling), jQuery for AJAX (optional but useful for smooth interactions).

Folder Structure
We'll follow the MVC pattern.

`to-do-app/
│
├── app.py                # Main Flask app
├── models.py             # Defines database models
├── views.py              # Handles the routes (controllers)
├── static/               # Contains CSS, JS, and images
│   ├── css/
│   ├── js/
├── templates/            # HTML templates
│   ├── base.html         # Main layout
│   ├── index.html        # Task list
│   ├── login.html        # Login form
│   ├── register.html     # Registration form
├── instance/             # Holds the SQLite database
│   └── to-do-app.db      # SQLite database file
└── .env                  # Environment variables (e.g., secret keys)`


