# Day 1
## Topics Covered
- Basic Flask Setup/Config
- Blueprints
- Templates
- Routes
- Dynamic Routes
- Static files
- Start Flask App

## Add flask environment variables:

- Windows
  - set FLASK_ENV=development
  - set FLASK_APP=<NAME-OF-PROJECT>(ie drone_inventory)
- Mac
  - export FLASK_ENV=development
  - export FLASK_APP=<NAME-OF-PROJECT>(ie drone_inventory)
 
[Flask Documentation](https://flask.palletsprojects.com/en/1.1.x/)

[Flask Blueprint Docs](https://flask.palletsprojects.com/en/1.1.x/blueprints/)

# Day 2
## Topics Covered
- Designing a Landing Page
- Flask-WTF
- Form Templates
- Jinja 2 'includes'
- Collecting Form Data

## Installations
Flask-WTF `pip install Flask-WTF` Email Validator `pip install email_validator`

# Day 3
## Topics Covered
- User Authentication
- Connecting Flask to a postgres database
- Flask-SQLAlchemy Models
- Flask SQL Migrations and Versions
- Flask Login and Login Manager

## Installations
Flask-SQLAlchemy `pip install Flask-SQLAlchemy`, Flask-Migrate `pip install Flask-Migrate`, 
Flask-Login `pip install flask-login`, psycopg2 (Windows) `pip install psycopg2`, psycopg2 (Mac/Linux) `pip install psycopg2-binary`

[Flask-SQLAlchemy Docs](https://flask-sqlalchemy.palletsprojects.com/en/2.x/)

[Flask-Migrate Docs](https://flask-migrate.readthedocs.io/en/latest/)

[Flask-Login Docs](https://flask-login.readthedocs.io/en/latest/)

# Day 4
## Topics Covered
- Tracking a User session with flask-login and Login Manager
- Displaying Personalized user data
- High level intro to HTTP requests and codes
- High level intro to API and JSON
- Using a GET request from Insomnia to GET data (from outside of our project)
- Creating table relationships with SQLAlchemy

## Installations
Flask-Marshmallow `pip install Flask-Marshmallow` Flask-Cors `pip-install Flask-cors` 
