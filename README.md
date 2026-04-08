Django Tweet App
A functional social media application built with Django that allows users to share thoughts and images in a streamlined environment.

Features
User Authentication: Secure Registration, Login, and Logout functionality.

Tweet Management: Create, Read, Update, and Delete (CRUD) operations for tweets.

Permissions: Users can only Edit or Delete their own tweets; other users' posts are read-only.

Media Support: Users can upload images with their tweets and edit them later.

Responsive UI: Styled using Bootstrap for a clean, mobile-friendly experience.

Technology Stack
Backend: Python, Django

Frontend: HTML, CSS, Bootstrap

Database: SQLite (default Django)

How to Run the Project
To get this project running locally, follow these steps:

Install Dependencies:

Bash
pip install -r requirements.txt
Apply Database Migrations:

Bash
python manage.py migrate
Start the Development Server:

Bash
python manage.py runserver
