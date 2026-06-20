# Task_Manager
taskmanager webapplicationProject Overview

Task Manager is a full-stack web application built using React, Django REST Framework, and MySQL.

The application allows users to create, view, update, filter, and delete tasks. Users can also track completed and pending tasks through a dashboard counter.



Technologies Used

Frontend

- React.js
- Axios
- CSS

Backend

- Django
- Django REST Framework

Database

- MySQL



Features Implemented

Task Management

- Add new tasks
- Task title (required)
- Task description (optional)
- Due date (optional)
- Priority selection (Low / Medium / High)

Task Tracking

- View all tasks
- Mark task as Done
- Mark task as Not Done (Undo)
- Delete tasks with confirmation

Filters

- Filter by Status
  
  - All
  - Pending
  - Done

- Filter by Priority
  
  - Low
  - Medium
  - High

Dashboard

- Display number of Pending Tasks
- Display number of Completed Tasks

API Operations

- GET Tasks
- POST Task
- PUT Task Update
- DELETE Task

---

Project Structure

TaskManager

├── backend

│   ├── taskmanager

│   ├── tasks

│   └── manage.py

│

└── frontend

├── public

└── src

    ├── App.jsx

    ├── App.css

    ├── index.js

    └── index.css

---

Database Design

Task Table

Field| Type
id| Integer
title| CharField
description| TextField
due_date| DateField
priority| CharField
completed| BooleanField
created_at| DateTimeField

---

Setup Instructions

Backend

Create virtual environment

python -m venv venv

Activate environment

venv\Scripts\activate

Install dependencies

pip install django
pip install djangorestframework
pip install mysqlclient
pip install django-cors-headers

Run migrations

python manage.py makemigrations
python manage.py migrate

Start Django server

python manage.py runserver

---

Frontend

Install dependencies

npm install
npm install axios

Start React application

npm start

---

HTTP Methods Used

Method| Purpose
GET| Retrieve Tasks
POST| Create Task
PUT| Update Task
DELETE| Remove Task

---

Future Enhancements

- User Authentication (Login/Register)
- Search Tasks
- Task Categories
- Email Reminders
- Dark Mode
- Pagination
- Task Sorting by Priority
- Task Editing Feature
- Profile Management
- Deployment using AWS / Render / Vercel

---

Learning Outcomes

Through this project, I learned:

- React Hooks (useState, useEffect)
- Axios API Integration
- REST API Development
- Django REST Framework
- CRUD Operations
- MySQL Database Integration
- Frontend and Backend Communication
- Component-Based Architecture
- Git and GitHub Version Control

---

Author

Hemapriya S
