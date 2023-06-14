# Overall Django Cheat Sheet

## Getting everything started

* python3.11 -m venv .venv
* source .venv/bin/activate
* mkdir django-things
* cd into the new directory
* pip install django
* django-admin startproject django_things_project .
  * command line script
  * startproject is the command
  * then the name of the project, in this case
* python manage.py migrate
* python manage.py startapp XXXXX
  * Where the XXXXX is the name of the new app
* Update the settings.py in the main folder for the project with the name of the app
  * Only needs to be the name of the app

* python manage.py runserver

* make views.py
* from django.views.generic import TemplateView
* HomePageView(TemplateView):
* make urls.py to define the routes
  * from django.urls.path
  * from .views imoprt HomePageView
  * only needs to contain one variable
    * urlpatterns
      * path('', HomePageView.as_view(), name = 'home')
* make a templates folder
  * make a html file that is inside of templates to be used as a foundation for all the other pages to inherit
  * emmet shortcut
    * type an ! and then hit enter for a base thing to get autofilled for html

* in settings.py
  * go down to templates
    * dirs point to the base template file

* flowbite for tailwind CSS
