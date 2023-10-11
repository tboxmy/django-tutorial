# django-tutorial
Basic tutorial example of Django 4 and Python 30.10.5

Demonstrate basics of model, view, template and admin control panel.

Django version 4.2.6
Python version 30.10.5

# Command lines

```pip install django
django-admin startproject demo
cd demo
python manage.py startapp myapp
```

Edit demo/settings.py and add myapp, myapp/templates folder

```python manage.py runserver

```

Edit myapp/models.py

```python manage.py makemigrations
python manage.py migrate

python manage.py createsuperuser
```

username admin/password

```python manage.py runserver

```

Open web browser to view results
http://127.0.0.1:8000/todos/
http://127.0.0.1:8000/admin
