release: python manage.py migrate
web: gunicorn ManagementSystem.wsgi
