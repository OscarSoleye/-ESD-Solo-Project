Django eCommerce Site
This Django project is an eCommerce website that allows users to browse and purchase products online. It is built using Django 3.2 and Python 3.9.

Installation:
Create a new Django project: django-admin startproject wale
Create a new Django app: python manage.py startapp store 
Install the requirements: pip install -r requirements.txt 
Migrate the database: python manage.py migrate 
Create a superuser: python manage.py create superuser 
Run the development server: python manage.py runserver


Features Wale’s Online Store includes the following features:
User authentication (login, logout, register) Product browsing (search) Shopping cart (add, remove, update quantities) Checkout (enter shipping and billing information) Order history and status tracking using charts
DJANGO_SECRET_KEY: the secret key for your Django project. These can be set in a .env file in the project root directory.
The database used is sqlite3
Usage After following the installation steps, you can access Wale’s Online Store site at http://localhost:8000/. 
To access the admin interface, go to http://localhost:8000/admin/ and enter your superuser credentials.
The Username is walesoleye, the password is djangodjango
