
##Intro

[Tutorial Link](https://docs.djangoproject.com/en/3.1/intro/tutorial01/)

- Create venv
`$ python3 -m venv .env`

- Activate venv
`$ source .env/bin/activate`

- Install Django
`$ pip3 install django`

- Check Version
`$ python3 -m django --version`

- Launch Server (Within Project Root)
`$ python3 manage.py runserver`

- Change port
`$ python3 manage.py runserver 8080`

### Models and dB
1. change models.py
2. run `python3 manage.py makemigrations` to create migra for changes
3. run `python3 manage.py migrate` to apply changes to dB


