# Task manager

Welcome to the Task Manager project! This Django-based application is designed to help users manage their tasks effectively. Whether you're organizing your personal to-do list.

# Features:
Task Management: Create, update, delete, and prioritize tasks effortlessly.
Due Dates: Set due dates for tasks to prioritize and manage deadlines effectively.
# Installation:
Clone Repository: Clone this repository to your local machine using git clone https://github.com/your-username/task-manager.git.
Navigate to Directory: Move into the project directory using cd task-manager.
Create Virtual Environment: Create a virtual environment to isolate project dependencies using python3 -m venv env.
Activate Virtual Environment: Activate the virtual environment:
On Windows: env\Scripts\activate
On macOS and Linux: source env/bin/activate
Install Dependencies: Install the project dependencies using pip install -r requirements.txt.
Database Setup: Configure your database settings in settings.py and run migrations:
Copy code
python manage.py makemigrations
python manage.py migrate
Run Server: Start the Django development server using python manage.py runserver.
Access Application: Open your web browser and go to http://localhost:8000 to access the application.
# Usage:
Task Creation: Create new tasks by clicking on the "Create a Task" button and filling out the required details.
Task Management: Update, delete, or mark tasks as complete/incomplete as needed.
