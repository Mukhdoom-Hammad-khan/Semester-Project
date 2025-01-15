Task Tracker - University Semester Project
This project is a simple task tracker application built using Flask and SQLite for the backend. The application allows users to register, log in, add tasks, mark tasks as completed, delete tasks, and export tasks as a CSV file. It includes a basic authentication system to ensure secure access to task management features.

Features
User Authentication: Users can register and log in to access their personalized task lists.
Task Management: Users can add tasks, edit their status, and delete tasks.
Task Export: Users can export their tasks to a CSV file.
Task Categories: Tasks can be categorized as Work, Personal, Shopping, or Other.
Technologies Used
Frontend: HTML, CSS (with a custom style for layout)
Backend: Python (Flask Framework)
Database: SQLite
Password Encryption: Flask-Bcrypt
User Authentication: Flask-Login
CSV Export: pandas library for generating CSV files
Project Structure
app.py: Main application file containing routes, models, and logic.
templates/: Contains HTML files for different pages (e.g., login, registration, task list).
static/: Contains the style.css file for custom styling.
tasks.db: SQLite database to store user data and tasks.
Setup Instructions
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/task-tracker.git
Navigate to the project directory:

bash
Copy code
cd task-tracker
Create a virtual environment (optional but recommended):

bash
Copy code
python -m venv venv
Activate the virtual environment:

On Windows:
bash
Copy code
venv\Scripts\activate
On macOS/Linux:
bash
Copy code
source venv/bin/activate
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the application:

bash
Copy code
python app.py
Access the application by visiting http://127.0.0.1:5002 in your browser.

Group Members & Contributions
Ajwad Rehman: Gave the idea for the project, worked on the backend with Flask (Python), and worked on the database.
Ahmed Raza: Worked on login functionality and index.html.
Mukhdoom Hammad Khan: Worked on base.html and registration functionality.
Muhammad Huzaifa Ali Sulehria: Worked on CSS and add_task.html.
License
This project is licensed under the MIT License.

Make sure to replace the link to your GitHub repository and adjust any details if necessary.
