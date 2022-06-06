# recipe-django-api
Recipe API project using django framework.

## Linting and Test
docker-compose run --rm app sh -c "flake8"
docker-compose run --rm app sh -c "python manage.py test"

docker-compose run --rm app sh -c "django-admin startproject app ."