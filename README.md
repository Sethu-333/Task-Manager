# Task-Manager
Task Manager is a web application built with Django and SQLite that helps users organize and manage their daily tasks efficiently. Users can create, update, delete, and mark tasks as completed. The app provides an intuitive interface to view tasks by their status, helping users stay productive and on track.


# Task Manager (Django)

A simple task manager web application built with Django and SQLite.

## Features
- Add, update, and delete tasks
- Mark tasks as completed
- View tasks by status

## Setup Instructions

1. Clone the repository and navigate into it:  
git clone https://github.com/yourusername/taskmanager.git  
cd taskmanager

2. Create and activate a virtual environment:  
On Windows:  
python -m venv venv  
venv\Scripts\activate  
On Mac/Linux:  
python3 -m venv venv  
source venv/bin/activate

3. Install dependencies:  
pip install -r requirements.txt

4. Run database migrations:  
python manage.py migrate

5. Start the development server:  
python manage.py runserver

6. Open your browser and go to:  
http://127.0.0.1:8000

---

Feel free to fork, contribute, or report issues!

---

## License

This project is licensed under the MIT License.
