# NeoX
This project is for demonstrating the basics of the Django framework in Python

## Prerequisites
  1.Python 3.6 or later
  
  2.Django

## Installation guide
Assuming that Python 3.6 or later has been installed, Django can be installed using the pip command, so type the following command to install Django

    pip install django

Then after that, download the repository and extact the zip files

Finally run the command,

For macOS/Linux:

    python3 manage.py runserver
    
For Windows:

    py -3 manage.py runserver
    
The server should be running in background, then go to the link [server](http://127.0.0.1:8000)
    
## Installing grappelli admin theme

I've used grappelli for the admin UI, so type the foll in cmd

    pip3 install django-grappelli
    
Else, the deploy server won't work properly

## Bypass Links

If you've started the server and running on your system, click the link below to go to the point directly!

[Admin](http://127.0.0.1/admin)

Admin privilege access:

**UserID**:admin

**Password**:admin

**This is just for adding books, users, groups etc**

### Note

I didn't publish my web app using Heroku due to some issues in my system! So, it works only as a local web app


