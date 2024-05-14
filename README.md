# Task Manager Mini-Project

![Task Manager](/taskmanager/static/images/Screenshot.png)

## About

This Task Manager application is built using the Flask framework, SQLAlchemy ORM, and Materialize CSS framework. It serves as a practical example of implementing CRUD (Create, Read, Update, Delete) operations in a web application. The app provides an intuitive graphical user interface for managing tasks efficiently.

## Features

- **Create Tasks**: Add new tasks with details.
- **Read Tasks**: View all tasks in a user-friendly interface.
- **Update Tasks**: Modify the details of existing tasks.
- **Delete Tasks**: Remove tasks no longer needed.

## Technologies Used

- **Flask**: A lightweight WSGI web application framework.
- **SQLAlchemy ORM**: Provides an object-relational mapping approach to handle database interactions.
- **Materialize CSS**: A modern responsive front-end framework based on Material Design.

## Deployment

The application is deployed and accessible at Heroku Task Manager (https://task-manager14-49ab8990d4cb.herokuapp.com/).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them:

`python -m pip install flask sqlalchemy materialize-css``

### Installing

A step by step series of examples that tell you how to get a development env running:

Clone the repository:

` git clone https://github.com/yourusername/task-manager.git``
 `cd task-manager``

### Install required packages:

`pip install -r requirements.txt``

### Initialize the database:

` python manage.py db init``
 `python manage.py db migrate``
`python manage.py db upgrade``

### Run the Flask application:

`flask run`
Navigate to http://localhost:5000 in your web browser to view the app.
