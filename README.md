# Set up requirements
```
 pip3 install virtualenvwrapper
 mkvirtualenv ltp
 workon ltp
 pip3 install -r requirements.txt
```

# Running
```
workon ltp
python manage.py makemigrations
python manage.py migrate

python manage.py runserver
```