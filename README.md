### Setup python version
In django-admin file (‎⁨Library⁩/Frameworks⁩/⁨Python.framework⁩/Versions⁩/3.7⁩) should be set proper version of python, e.g.:
> #!/usr/local/bin/python3

### Start working
To start server type:
> python3 manage.py runserver

If server has migration errors, type following command:
> python3 manage.py migrate

To create super user enter:
> python3 manage.py createsuperuser --username=myName --email=myEmail 

To create app:
> python3 manage.py startapp appName