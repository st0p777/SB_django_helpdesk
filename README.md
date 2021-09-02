# SB_django_helpdesk
django_helpdesk wrapped in wemake-django-template
После клонирования репозитория в SB_django_helpdesk/sb-django-helpdesk/config/ нужно создать файл .env   
Чтобы поднять сервер нужно из директории sb-django-helpdesk( где лежат докер файлы) выполнить команды:
docker-compose build   
docker-compose run --rm web python manage.py migrate
docker-compose up
После старта сервера по адресу http://localhost:8000/helpdesk/ откроется(если всё получиться) страница helpdesk Помощь и поддержка.
