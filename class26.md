# Intro to Django

## Reading Questions

* What are the key components of the Django framework and how do they contribute to building a web application?
  * Model - The information itself and how it is to be stored/relates to other information
  * View - Seems to be the main controller which updates the information in the Model segment
  * Template - Responsible for shoing the information or how the page is structured for viewing

* Explain the role of Django's MTV (Model-View-Template) architecture and how it handles a typical web request-response cycle.
  * Input from the user first goes into view processing
  * The view interacts with the model to see if the information needed is already there or if additional information is needed as well as what is to be displayed
  * The view then sends the information to the template which will determine how the information is to be displayed to the user

* What is the purpose of Tailwind CSS and how does it differ from Bootstrap CSS?
  * Tailwind CSS takes a utility-first approach and has a number of customizable options when it comes to styling while it's primiarily there to provide either the functionality portion or a rough outline of how the component will look on the page.
  * For Boostrap CSS it's more or less a 'pick and choose from the menu' approach with limited number of 'substitutions' which can be made in terms of style.

## Readings

* [Getting started with Django](https://www.djangoproject.com/start/)
* [How Django works behind the scenes](https://wsvincent.com/how-django-works-behind-the-scenes/)
* [What is Tailwind CSS?](https://blog.hubspot.com/website/what-is-tailwind-css)
* [What is Django?](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Introduction)
* [First Django App - Part 1](https://docs.djangoproject.com/en/4.1/intro/tutorial01/)
* [First Django App - Part 2](https://docs.djangoproject.com/en/4.1/intro/tutorial02/)
* [Tailwind CSS Django - Flowbite](https://flowbite.com/docs/getting-started/django/)
