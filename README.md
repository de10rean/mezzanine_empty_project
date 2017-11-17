# MEZZANINE EMPTY PROJECT
It is for you - peaple that tired to do it again and again.  

# QUICK START

## STEP #1
Fork with repository to create your own mezzanine-project

## STEP #2
Clone it to your machine

## STEP #3
Create virtual environment for your project and install dependencies by command:<br>
`pip install -r requirements.txt`

## STEP #4 (Little bit configure)
#### DB config
You have 2 ways:
* Configure it int settings.py
* Configure it int settings_local.py (privilege)
[This](https://docs.djangoproject.com/en/1.11/ref/settings/#databases) can help you
#### Static files config
You can use [that](https://docs.djangoproject.com/en/1.11/ref/settings/#static-files) piece of Django documentation

## STEP #4
Migrate your DB by using command:<br>
`python manage.py migrate`

## STEP #5 (optional)
Create admin user for test that you project works, with this command:<br>
`python manage.py createsuperuser`

# USED DISTRIBUTIONS
python >= 3.5
Dajngo == 1.10
Mezzanine == 4.2.3

# ADDITIONAL INFO
That code contain main project app directory named `projectapp`. You can rename
it wherever you want - that change does not 'broke the system'
