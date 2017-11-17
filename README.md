# MEZZANINE EMPTY PROJECT
It is for you - people that tired to do it again and again.  

# QUICK START

## STEP #1

Duplicate it repository

* Create a bare mirrored clone of the repository
```bash
git clone https://github.com/de10rean/mezzanine_empty_project.git <your project directory>
```
* Set the push location to your mirror.
```bash
cd <your project directory>
git remote set-url --push origin https://github.com/<your user>/<your repository> 
```
  
## STEP #2
Create virtual environment for your project and install dependencies by command:<br>
`pip install -r requirements.txt`

## STEP #3 (Little bit configure)
#### DB config
You have 2 ways:
* Configure it in settings.py
* Configure it in settings_local.py (not tracked by git)
[This](https://docs.djangoproject.com/en/1.11/ref/settings/#databases) can help you
#### Static files config
You can use [that](https://docs.djangoproject.com/en/1.11/ref/settings/#static-files) piece of Django documentation

## STEP #4
Migrate your DB by using command:<br>
`python manage.py migrate`

## STEP #5 
Run dev server by using command:<br>
`python manage.py runserver`<br>
By default your project will be able on '127.0.0.1:800'

## STEP #6 (optional)
Create admin user for test that you project works, with this command:<br>
`python manage.py createsuperuser`

# USED DISTRIBUTIONS
python >= 3.5<br>
Dajngo == 1.10<br>
Mezzanine == 4.2.3<br>

# ADDITIONAL INFO
That code contain main project app directory named `projectapp`. You can rename
it wherever you want - that change does not 'broke the system'
