# Authentication and Production

## Questions

* What is the primary purpose of JSON Web Tokens (JWTs) and how do they work in terms of encoding and decoding data?
  * The primary purpose of a JWT is to keep a record of someone being authenticated along with the permissions that that individual has so they don't have to authenticate every time they wish to access information (when going to different sites). The token comes in three parts, a declaration that it is a JSOPN file with the encryption key, the content, and a signature which repeats the owner of the token.

* How does JWT Authenication integrate with Django REST Framework to secure API endpoints and what are the key components involved in this process?
  * The JWT is passed in when someone is trying to access the endpoint and on the server side if that endpoint requires a particular authorization it will check before that page or component is processed.

* Why is Django's built-in runserver not suitable for production environments and what are some alternative server options that should be considered for deploying a Django application?
  * Django's runserver is great and wonderful for development however it is not intended for large-scale requests and has a number of security concerns over a typical production environment. One of the suggested location would be Gunicorn.

## Readings

* [JSON Web Tokens](https://jwt.io/introduction/)
* [DRF JWT Authentication](https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html)
* [Django Runserver Is Not Your Production Server](https://build.vsupalov.com/django-runserver-in-production/)
* [White Noise](https://whitenoise.readthedocs.io/en/stable/django.html)
* [JWT with DRF](https://www.youtube.com/watch?v=Fhcn2qx-4VQ)
* [Gunicorn](https://gunicorn.org/)
* [Django Migration Primer](https://realpython.com/django-migrations-a-primer/)
