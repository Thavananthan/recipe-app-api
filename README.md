# recipe-app-api

# docker build .

# docker-composer bulid

# docker-compose run --rm app sh -c "flake8"

<!-- create project in side the composer  -->

# docker-compose run --rm app sh -c "django-admin startproject app ."

<!-- running cmd -->

# docker-compose up

<!-- other testing cmd -->

# docker-compose run --rm app sh -c "python manage.py test" .

<!-- after model createtion makemigration -->

# docker-compose run --rm app sh -c "python manage.py makemigrations"

<!-- model migrate to db -->

# docker-compose run --rm app sh -c "python manage.py wait_for_db && python manage.py migrate"

<!-- create super user cmd -->

# docker-compose run --rm app sh -c "python manage.py createsuperuser"

<!-- create app  -->

# docker-compose run --rm app sh -c "python manage.py startapp recipe"
