# recipe-app-api

docker setup:

docker build .
docker-compuse build


create new project in docker:

docker-compose run app sh -c "django-admin.py startproject app ."


run local tests:

docker-compose run app sh -c "python manage.py test"
