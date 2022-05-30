web: gunicorn -b "0.0.0.0:$PORT" -w 3 blogapp.wsgi
release: python manage.py migrate