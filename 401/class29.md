# Django Custom User

## Reading Questions

* What are the key benefits of using a Django Custom User Model and how does it differ from the defaut Django User Model?
  * Overall just more control over what information can be stored about a user (fields, throw in authentication information, adaptable schema, etc.)

* Explain the process of creating and implementing a Custom User Model in Django including the necessary changes to settings.py and the required model fields.
  * Make an accounts app
  * Mostly only deal with AbstractBaseUser
  * Update settings.py to allow for a new CustomUser model under AUTH_USER_MODEL
  * Update models.py in accouns app
  * Make forms.py
  * import CustomUser from .models
  * Update admin.py
  * Then migrate

* What is DjangoX and how does it complement or extend the functionality of Django? Provide an example use case for incorporating DjangoX in a project.
  * Not really sure? The documentation doesn't seem to give too much?

## Readings

* [Django Custom User Model](https://learndjango.com/tutorials/django-custom-user-model)
* [DjangoX](https://github.com/wsvincent/djangox)
* [Creating a Custom User Model](https://www.youtube.com/watch?v=eCeRC7E8Z7Y&t=59s)
* [Abstract User, User Profile and Signals in Django](https://www.youtube.com/watch?v=EudKs1HPUfE)
* [Subsituting a custom User model](https://docs.djangoproject.com/en/3.0/topics/auth/customizing/#auth-custom-user)
