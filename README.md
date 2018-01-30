pip3 install pipenv
pipenv install

pipenv shell
python manage.py makemigrations
python manage.py migrate

python manage.py runserver