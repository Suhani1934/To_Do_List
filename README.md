# 📝 To-Do List Application with Django

## Overview

This is a simple to-do list web application built using the Django framework. It allows users to create, view, and delete tasks. This project demonstrates basic Django concepts, including models, views, templates, and database interaction.

## 🚀 Features

* **Create tasks:** Users can add new tasks to their to-do list.
* **View tasks:** Users can see all the tasks in their to-do list.
* **Delete tasks:** Users can remove tasks from their to-do list.
* **Django Admin Interface:** Utilize Django's admin interface to manage tasks.

## 🛠️ Technologies Used

* **Django:** A high-level Python web framework.
* **Python:** The programming language used to build the application.
* **HTML:** Used for the structure of the web pages.
* **CSS:** Used for styling the web pages.
* **Bootstrap:** A CSS framework for responsive design.
* **SQLite:** The default database used by Django (suitable for development).

## 📦 Setup Instructions

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Suhani1934/To_Do_List.git](https://github.com/Suhani1934/To_Do_List.git)
    cd To_Do_List
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    ```
    * On Windows, activate it with:
        ```bash
        venv\Scripts\activate
        ```
    * On macOS and Linux, activate it with:
        ```bash
        source venv/bin/activate
        ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Apply database migrations:**
    ```bash
    python manage.py migrate
    ```

5.  **Run the development server:**
    ```bash
    python manage.py runserver
    ```

6.  **Access the application:**
    Open your web browser and go to `http://127.0.0.1:8000/` to view the to-do list.
    
7.  **Access the Django Admin Interface:**
     Open your web browser and go to `http://127.0.0.1:8000/admin/`.  You'll need to create a superuser to log in:
     ```bash
     python manage.py createsuperuser
     ```
     Follow the prompts to enter a username, email, and password.
