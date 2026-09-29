# expese_manager

A Flask app to track and manage expenses, built step by step as a teaching project.

## Contents

- `app.py`: Flask app and routes
- `templates/`: base, landing, login and register pages
- `static/`: stylesheet and JavaScript
- `database/db.py`: SQLite helpers. This file is currently a placeholder with instructions for the database setup step

## Running

    pip install -r requirements.txt
    flask --app app run

`pytest` and `pytest-flask` are in `requirements.txt` for testing.
