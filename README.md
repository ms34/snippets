# Snippets

code highlighting Web API with Django REST framework

### Installation

First ensure you have python globally installed in your computer. If not, you can get python [here](python.org).


Git clone this repo to your PC

    $ git clone https://github.com/ms34/snippets.git
    $ cd snippets

Create a virtual environment

    For Linux an mac
    $ python3 -m  venv env && source .env/bin/activate

    For Windows
    $ python -m  venv env && .\env\Scripts\activate  

Install dependencies

    $ pip install -r requirements.txt

Make migrations & migrate

    $ python manage.py makemigrations && python manage.py migrate

Create Super user

    $ python manage.py createsuperuser

### Launching the app

    $ python manage.py runserver
