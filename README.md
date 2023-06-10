# Snippets

Code highlighting Web API with Django REST framework

### Installation

First, ensure you have Python globally installed on your computer. If not, you can get Python [here](python.org).


Git clone this repo to your PC

    $ git clone https://github.com/ms34/snippets.git
    $ cd snippets

Create a virtual environment

    For Windows
    $ python -m  venv env && .\env\Scripts\activate  

    For Linux and mac
    $ python3 -m  venv env && source .env/bin/activate

Install dependencies

    $ pip install -r requirements.txt

Make migrations & migrate

    $ python manage.py makemigrations snippets
    $ python manage.py migrate snippets

Create Super user

    $ python manage.py createsuperuser

### Launching the app

    $ python manage.py runserver
