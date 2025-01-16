# Birthday Registry

A full-stack web application that manages birthday records through a clean interface. Built as part of Harvard's CS50 course.

## Features

- Add new birthday entries with name and date
- View all stored birthdays in a tabulated format
- Delete existing birthday records
- Data persistence using SQLite database

## Technologies

- **Frontend**: HTML, CSS
- **Backend**: Python (Flask)
- **Database**: SQLite
- **Additional**: CS50 Library

## Setup

1. Ensure you have Python and Flask installed
2. Clone this repository
3. Run the application using `python app.py`
4. Access the application through your browser at `http://127.0.0.1:5000/`

This setup will allow you to manage birthdays effectively through a user-friendly interface.

## Install dependencies

bash
pip install Flask
pip install cs50

## Run the application

bash
python app.py

## Project Structure

birthdays/

├── app.py              # Flask application logic

├── birthdays.db        # SQLite database

├── static/

    └── styles.css      # CSS styling

└── templates/

     └── index.html      # Main page template

## Usage

- Access the application through your web browser at `http://localhost:5000`
- Enter a name, month, and day to add a new birthday
- View all birthdays in the table below
- Click "Delete" next to any entry to remove it

## Credits

This project was completed as part of [Harvard's CS50 course](https://cs50.harvard.edu/x).