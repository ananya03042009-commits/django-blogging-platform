# Django Blogging Platform

A simple blogging platform developed using Python and Django as a web development project.

## Features

* View blog posts on the homepage
* Read individual blog posts
* Display post author, category, and publication date
* Manage blog posts through Django Admin
* About page
* Custom CSS styling

## Technologies Used

* Python
* Django
* HTML
* CSS
* SQLite

## Project Structure

```text
django-blogging-platform/
├── blog/
├── blog_project/
├── manage.py
├── requirements.txt
├── README.md
└── .gitignore
```

## Installation and Setup

1. Clone or download this repository.
2. Open a terminal in the project directory.
3. Create and activate a Python virtual environment.
4. Install the dependencies:

```bash
pip install -r requirements.txt
```

5. Apply database migrations:

```bash
python manage.py migrate
```

6. Start the development server:

```bash
python manage.py runserver
```

7. Open `http://127.0.0.1:8000/` in your browser.

## Django Admin

Access the admin panel at `http://127.0.0.1:8000/admin/`.

Create an administrator account using:

```bash
python manage.py createsuperuser
```

## Future Enhancements

* Search functionality
* User authentication
* Comments on blog posts
