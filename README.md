# Flask TODO App

Welcome to my Flask TODO app! This is a simple application built using Flask for the backend and SQLAlchemy for database management. This project marks the beginning of my journey into backend development with Python.

## Project Overview

This TODO app allows users to:

- **Add** a new TODO item with a title and description.
- **Read** existing TODO items.
- **Update** existing TODO items.
- **Delete** TODO items.

All data is stored using SQLAlchemy, an Object-Relational Mapping (ORM) tool that simplifies database interactions.

## Features

- **CRUD Operations**: Create, Read, Update, and Delete TODO items.
- **Database Integration**: Uses SQLAlchemy to handle database operations.
- **Flask Framework**: Serves as the backend framework to manage requests and responses.
- **Frontend Integration**: Integrates with a basic frontend to demonstrate how Flask can handle dynamic content and data interaction.

## Installation

To get started with the Flask TODO app, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/flask-todo-app.git
   cd flask-todo-app

2. **Set Up a Virtual Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  
   # On Windows use `venv\Scripts\activate`
3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt

4. **Set Up the Database**

   ```bash
   flask db upgrade
5. **Run the application**

   ```bash
   flask run or python -m app.py

   The application will be available at http://127.0.0.1:/8000.

# Features in Detail
Flask Backend

Flask is a lightweight WSGI web application framework in Python. It is designed to be simple and easy to extend, allowing for fast development and easy integration with frontend technologies. Here’s how it handles various backend tasks in this app:

- **Routing**: Flask maps URLs to functions using routes. This app defines routes for creating, reading, updating, and deleting TODO items.
- **Request Handling**: Flask processes incoming requests and dispatches them to the appropriate route function.
- **Templates** : Flask uses Jinja2 templates to render HTML pages with dynamic data.


**SQLAlchemy Integration**

SQLAlchemy is used to manage database interactions with an ORM approach:
- **Models**: Define classes representing database tables. This app uses a Todo model to represent TODO items.
- **Sessions**: Manage database transactions and queries.

**Frontend Integration**
The app includes a basic frontend that interacts with the Flask backend:
- **HTML Forms**: Allow users to submit data for creating and updating TODO items.


## Forking the Repository

Feel free to fork this repository and make your own modifications. To fork the repository:

1. Go to the GitHub page of this repository.

2. Click on the Fork button in the top-right corner of the page.

3. Clone your forked repository to your local machine:
    ```bash
    git clone https://github.com/itz-daxh94/First_Flask_app-Todo-Render
    cd flask-todo-app

4. Make your changes, commit them, and push them to your forked repository.


## Contributing

If you have suggestions for improvements or find any issues, please open an issue or submit a pull request. Contributions are always welcome!


