# recipe-app-api
	This is a fully functioning REST API with Django, Python and TDD.
	While making this project, i've learned how to setup project using Docker and configure Travis-CI.
	Created endpoints, added listing, filtering and upload images to endpoints.


## Install guide

##### Clone the repo

```bash
$ git clone https://github.com/Kburak/django-restful-api.git
$ cd django/django-restful-api
```
##### Create the virtualenv and activate it
```bash
$ python3 -m venv venv
$ . venv/bin/activate
```

##### Or on Windows cmd::
```bash
$ py -3 -m venv venv
$ venv\Scripts\activate.bat
```

##### Build Docker 
```bash
$ docker-compose build
```

##### Make Migrations
```bash
$ docker-compose run --rm app sh -c "python manage.py makemigrations"
```

##### Run the app
```bash
$ docker-compose up
```
