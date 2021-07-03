release: python manage.py makemigrations --no-input
release: python manage.py migrate --no-input

web: python manage.py collectstatic --noinput
web: gunicorn library.wsgi
web: python manage.py runserver
