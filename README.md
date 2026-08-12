# Mini Notion — Personal Notes App

A simple web application to create, read, update, delete, and search personal notes.
Built with Python, Flask, and SQLite.

## Features
- Create notes with a title and body
- View all notes on a clean card-based homepage
- Edit any note
- Delete notes with confirmation
- Search notes by keyword (title + body)
- Responsive modern UI

## Tech Stack
- Python 3
- Flask
- SQLite
- HTML/CSS (Jinja2 templates)

## Getting Started

### Install dependencies
pip install -r requirements.txt

### Run the app
python app.py

Open http://localhost:5000 in your browser.

## Project Structure
mini-notion/
├── app.py              # Flask routes + SQLite database
├── requirements.txt
├── README.md
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── form.html
│   └── view.html
└── static/
    └── style.css
