Setting Up The Project
Now run the following command in your shell to create a Django project.

django-admin startproject SolveRahul
This will generate a project structure with several directories and python scripts.

├── SolveRahul
│   ├── __init__
│   ├── settings
│   ├── urls
│   ├── wsgi
├── manage


Next Create Blog Application 

cd  SolveRahul
python manage.py startapp Blog
These will create an app named blog in our project.

├── db<span class="hljs-selector-class">.sqlite3</span>
├── SolveRahul
│   ├── __init__
│   ├── settings
│   ├── urls
│   ├── wsgi
├── manage
└── Blog
    ├── __init__
    ├── admin
    ├── apps
    ├── migrations
    │   └── __init_
    ├── models
    ├── tests
    └── views



python manage.py migrate
python manage.py makemigrations

python manage.py runserver