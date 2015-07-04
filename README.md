# Django REST API Example
A simple application that manipulates code snippets with highlighted syntax
using a REST API created with [Django Rest Framework](http://www.django-rest-framework.org)

## Requirements
* Django 1.8
* Django Rest Framework
* Pygments

## Run the app
Once installed the requirements: 
``` python
python manage.py makemigrations snippets
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Now you can go to `http://127.0.0.1:8000` and browse the REST API.

> Note that you need to login in order to be allowed to create and update snippets.
