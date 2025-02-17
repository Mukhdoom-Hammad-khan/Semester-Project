# Task Tracker - University Semester Project
This project is a simple task tracker application built using Flask and SQLite for the backend. The application allows users to register, log in, add tasks, mark tasks as completed, delete tasks, and export tasks as a CSV file. It includes a basic authentication system to ensure secure access to task management features.

## Features
User Authentication: Users can register and log in to access their personalized task lists.<br>
Task Management: Users can add tasks, edit their status, and delete tasks.<br>
Task Export: Users can export their tasks to a CSV file.<br>
Task Categories: Tasks can be categorized as Work, Personal, Shopping, or Other.<br>

## Technologies Used
Frontend: HTML, CSS (with a custom style for layout)<br>
Backend: Python (Flask Framework)<br>
Database: SQLite<br>
Password Encryption: Flask-Bcrypt<br>
User Authentication: Flask-Login<br>
CSV Export: pandas library for generating CSV files<br>

## Project Structure
app.py: Main application file containing routes, models, and logic.<br>
templates/: Contains HTML files for different pages (e.g., login, registration, task list).<br>
static/: Contains the style.css file for custom styling.<br>
tasks.db: SQLite database to store user data and tasks.<br>

## Setup Instructions

### Clone the repository:

```bash
git clone https://github.com/Mukhdoom-Hammad-khan/Semester-Project.git
```
### Navigate to the project directory:

```bash
cd task-tracker
```
### Create a virtual environment (optional but recommended):

```bash
python -m venv venv
```
### Activate the virtual environment:

On Windows:

```bash
venv\Scripts\activate
```

On macOS/Linux:

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

### Run the application:

```bash
python app.py
```
Access the application by visiting http://127.0.0.1:5002 in your browser.

## File Structure

```graphql
interactive-python-web-app/
├── instance/
│   └── tasks.db
├── static/
│   └── style.css
├── templates/
│   |── index.html
│   |── add_task.html
│   |── base.html
│   |── register.html
│   └── login.css
├── app.py
└── README.md
```

## Group Members & Contributions
Ajwad Rehman: Gave the idea for the project, worked on the backend with Flask (Python), and worked on the database.<br>
Ahmed Raza: Worked on login functionality and index.html.<br>
Mukhdoom Hammad Khan: Worked on base.html and registration functionality.<br>
Muhammad Huzaifa Ali Sulehria: Worked on CSS and add_task.html.<br>

## License
This project is licensed under the [MIT](LICENSE).

Make sure to replace the link to your GitHub repository and adjust any details if necessary.
