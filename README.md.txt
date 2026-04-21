============================================================
PROJECT MANAGEMENT TOOL - INTERNSHIP PROJECT SUBMISSION
============================================================

DEVELOPER INFORMATION:
----------------------
Name: Vaibhavi
University: Shivaji University
Degree: B.Tech in Computer Science
Project: Project Management & Task Tracking System

PROJECT OVERVIEW:
-----------------
This is a comprehensive Project Management application designed 
to help teams organize tasks, track project progress, and 
manage deadlines. It features a structured hierarchy of 
Projects, Boards, and Tasks with a focus on real-time updates.

TOOLS & TECHNOLOGIES USED:
--------------------------
- Web Framework: Django / Django REST Framework
- Programming: Python
- Database: MySQL (via XAMPP / MariaDB)
- API Security: JWT (JSON Web Tokens) for Authentication
- Environment: Python Virtual Environment

KEY FEATURES:
-------------
1. Auth System: Secure User Registration and JWT-based Login.
2. Project Creation: Ability to create multiple projects with owners.
3. Task Boards: Kanban-style boards to organize tasks by status.
4. Task Management: Create, edit, and assign tasks with deadlines.
5. Database Integration: Full MySQL/MariaDB backend for data persistence.
6. Responsive Dashboard: A clean interface to view overall project health.

HOW TO RUN THIS PROJECT:
------------------------
1. Open your terminal in the project root folder.
2. Activate your environment:
    Scripts\activate
3. Install the requirements:
    pip install django djangorestframework djangorestframework-simplejwt pymysql cryptography
4. Database Setup:
    - Ensure XAMPP MySQL is running.
    - Create a database named 'project_db' in phpMyAdmin.
5. Setup the data:
    python manage.py makemigrations
    python manage.py migrate
6. Create an administrator account:
    python manage.py createsuperuser
7. Start the application:
    python manage.py runserver
    Then go to: http://127.0.0.1:8000/

============================================================
Developed by Vaibhavi | 2026
============================================================