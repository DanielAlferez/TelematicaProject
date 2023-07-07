web: gunicorn login_rest.wsgi --log-file -
web: python manage.py migrate && gunicorn login_rest.wsgi
