# 📝 Django Blog Website

A full-featured blog application built with **Django** and styled using **Bootstrap 5**. This app allows users to **create, read, update, and delete** blog posts, with support for **image uploads**, clean responsive design, and easy navigation.

## 🚀 Features

- Responsive UI with Bootstrap 5
- Create, update, delete blog posts
- Upload and display images with each post
- Full CRUD functionality
- User-friendly form design
- Media file support

## 🛠 Tech Stack

- Backend: Django
- Frontend: HTML5, CSS3, Bootstrap 5
- Database: SQLite (default with Django)
- Language: Python 3

## 📁 Project Setup
Create a virtual environment & activate it ->
python -m venv venv ->
source venv/bin/activate (or)  # Windows: venv\Scripts\activate

Install dependencies:->
pip install -r requirements.txt

Apply migrations:->
python manage.py makemigrations ->
python manage.py migrate

Run the development server
python manage.py runserver

Open in your browser
http://127.0.0.1:8000/
