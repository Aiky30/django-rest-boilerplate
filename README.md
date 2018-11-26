# django-rest-boilerplate

## Installation

Create an environment for the project
Clone the project into the environment

install the packages for the project
```
pip install -r ./requirements.txt
```

Prepare the DB
```
python manage.py migrate
```

Create a super user
```
python manage.py createsuperuser
```

Run the development server
```
python manage.py runserver
```

Login to the site by visiting the following in a web browser: http://127.0.0.1:8000/admin/

## Misc

Commands used to create this project
```
django-admin startproject example_project
django-admin startapp example_app
```

Configured Rest using the following docs: https://www.django-rest-framework.org/#requirements
