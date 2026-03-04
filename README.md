

* * * * *

Modern Flask To-Do App
======================

A simple, modern web-based To-Do application built using Flask and SQLite.\
The application allows users to manage daily tasks with persistent storage and a clean Bootstrap-powered interface.

* * * * *

 Project Overview
-------------------

This project demonstrates how to build a full-stack web application using:

-   Backend framework (Flask)

-   Database (SQLite)

-   ORM (SQLAlchemy)

-   Frontend styling (Bootstrap 5)

The application supports full task lifecycle management while maintaining a clean and responsive user interface.

* * * * *

 Features
-----------

-   Add new tasks

-   Delete tasks

-   Mark tasks as completed

-   Persistent storage using SQLite

-   Clean and responsive UI using Bootstrap 5

-   Simple and modular Flask structure

* * * * *

 How It Works
---------------

1.  User enters a task in the input field

2.  Flask processes the request

3.  Task is stored in SQLite database using SQLAlchemy

4.  Tasks are dynamically rendered on the homepage

5.  Updates (delete/complete) are reflected in the database

* * * * *

 Application Workflow
-----------------------

```
User Input (Task)
        ↓
Flask Route Handling
        ↓
SQLAlchemy ORM Operation
        ↓
SQLite Database Storage
        ↓
Updated Task List Rendered
        ↓
Bootstrap UI Display

```

* * * * *

 Tech Stack
-------------

### Backend

-   Python 3.x

-   Flask (Web framework)

### Database

-   SQLite (Lightweight relational database)

-   SQLAlchemy (ORM for database interaction)

### Frontend

-   HTML

-   Bootstrap 5 (Responsive styling)

* * * * *

 Project Structure
--------------------

```
Modern_Flask_Todo_App/
│
├── app.py             
├── templates/         
│   └── index.html
├── static/            
├── todo.db             
├── requirements.txt
└── README.md

```

* * * * *

 Installation & Setup
-----------------------

###  Clone the Repository

```
git clone https://github.com/your-username/Modern-Flask-Todo-App.git
cd Modern-Flask-Todo-App

```

###  Create Virtual Environment (Recommended)

```
python -m venv venv
venv\Scripts\activate

```

###  Install Dependencies

```
pip install -r requirements.txt

```

* * * * *

 Run the Application
----------------------

```
python app.py

```

Open your browser and go to:

```
http://127.0.0.1:5000

```

* * * * *

 Database
-----------

The application uses SQLite:

-   Automatically creates `todo.db`

-   Stores tasks persistently

-   Uses SQLAlchemy ORM for structured database operations

* * * * *

 Privacy & Cost
-----------------

-   Runs entirely locally

-   No external APIs

-   No cloud services required

-   100% free and open-source

* * * * *

 Learning Outcomes
--------------------

Through this project:

-   Built a full-stack Flask application

-   Integrated SQLite with SQLAlchemy ORM

-   Implemented CRUD operations

-   Structured a Flask project professionally

-   Designed responsive UI using Bootstrap

* * * * *

 Future Enhancements
----------------------

-   Edit existing tasks

-   Due dates and reminders

-   Task categories or priority levels

-   User authentication system

-   Deployment on cloud platforms (Heroku, Render, etc.)

* * * * *

 Use Cases
------------

-   Beginner Flask practice

-   CRUD application demonstration

-   Portfolio web development project

-   Backend + database integration learning

* * * * *

 Author
------------

Anjana S V

* * * * *

