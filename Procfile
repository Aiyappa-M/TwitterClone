web: gunicorn TwitterClone.wsgi:application --log-file - --log-level debug
python3manage.py collectstatic --noinput
manage.py migrate