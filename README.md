# Django Task Manager

A simple task management system built with Django.

## Overview

This project is a task management system implemented using Django, a high-level Python web framework. It allows users to register, log in, create, view, update, and delete tasks. Each task is associated with the user who created it, ensuring privacy and data integrity.

## Features

- User authentication (registration and login)
- Task creation, listing, detail view, update, and deletion
- Responsive and user-friendly interface

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/django-task-manager.git

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt

3. Apply database migrations:
   ```bash
   python manage.py migrate
   
4. Run the development server:
   ```bash
   python manage.py runserver

Access the application at http://localhost:8000/register

## Usage

- Register a new account or log in with an existing account.
- Create tasks by clicking on the "Add Task" button.
- View, update, or delete tasks from the task list.
- Log out when done.
