# GA Cohorts Management Django

# Back Story
General Assmebly needs a system to manage their incoming students. As we all know General Assembly is a bootcamp for upskill and career changes in technology. General Assembly conducts the following courses:

1. Software Engineering Immersive a.k.a SEI
2. Data Science Immersive a.k.a DSI
3. Digital Marketing Accelerated a.k.a DMA
4. Frontend Web Development a.k.a FEWD
5. JavaScript Development a.k.a JSD

General Assembly would like create a student table so as to know what student are currently enrolled in each course. Note: One student can take only one course at a time.

# Deliverables
1. User should be able to create a course via a form
1. User should be able to create a student via a form
1. User should be able to add course to student via a form.

## Getting Started
- Clone this repository
- Create a django project `django-admin startproject generalassembly`
- Install Django `pipenv install django`
- Start python virtual environment `pipenv shell`
- Create a django app `python manage.py startapp school`
- When complete send a pull request to with a readme containing screenshots of your app.

## Helper
Since we have all agreed to use Postgresql as the Database for our app. Here is the hint on how to set it up.
1. On your terminal run `createdb <appname_development>`
2. Add to `your settings.py` under database
```python
  DATABASES = {
    # 'default': {
    #     'ENGINE': 'django.db.backends.sqlite3',
    #     'NAME': BASE_DIR / 'db.sqlite3',
    # }
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': '<database name>',
        'USER': '<ebere>',
        # 'PASSWORD': '<ebere>', # only required if on windows
        'HOST': 'localhost',
        'PORT': 5432
    }
}
```




