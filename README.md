# Library Management System

## Overview




<img width="1533" height="787" alt="5623d875-b8b1-4a55-9b8d-cde4606cc077" src="https://github.com/user-attachments/assets/fb6194d3-e488-4607-aec5-4374e1c02d1c" />


This project is a simple Django web application that manages a library of books.
It includes a web UI for browsing books and a REST API for creating, reading, updating, and deleting book records.

## What is an API?

An API (Application Programming Interface) is a set of rules that allows different software applications to communicate with each other.
In this project, the Django REST Framework provides an API for clients to interact with the book data over HTTP.

## What is an application?

An application is a software program designed to perform tasks for users.
This project is a web application because it runs on a server and provides an interface that users can access through a browser or other client.

## Features

- Django web application structure
- REST API endpoints for books
- Simple browser-based UI for users
- SQLite database for local development

## Requirements

- Python 3.10 or later
- `pip`

## Installation

1. Create a virtual environment:
   ```powershell
   python -m venv .venv
   ```
2. Activate the virtual environment:
   - PowerShell:
     ```powershell
     .\.venv\Scripts\Activate.ps1
     ```
   - Command Prompt:
     ```cmd
     .\.venv\Scripts\activate.bat
     ```
3. Install dependencies:
   ```powershell
   pip install -r requirements.txt
   ```
4. Apply database migrations:
   ```powershell
   python manage.py migrate
   ```

## Running the Project

Start the Django development server:

```powershell
python manage.py runserver
```

Then open the browser at:

```
http://127.0.0.1:8000/
```

## API Endpoints

The book API is available under `/api/books/`.

- `GET /api/books/` — list all books
- `POST /api/books/` — create a new book
- `GET /api/books/<id>/` — retrieve a book
- `PUT /api/books/<id>/` — update a book
- `DELETE /api/books/<id>/` — delete a book

## Notes

- Use the virtual environment for all development commands.
- This project uses SQLite by default, so it works locally without extra database setup.
# LBM-Github-co-
