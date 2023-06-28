# Django REST Framework & Docker

## Reading Questions

* What are the key componenets of a Docker container and how do they help streamline the development and deployment of applictions?
  * The key components of a Docker container are: images, image builds, image layers, and containers
    * Images - An all in one file encompassing all dependencies and code
    * Image build - the version of the image created
    * Image layers - each image is made up of multiple different layers such that it saves time when a build is made since many of the layers are pre-built and shared
    * Containers - a runtime environment for a Docker image

* Describe the primary steps involved in building a library website using Django including essential components like models, views, and tempates.
  * Create a virtual environment
  * Create a project
  * Migrate to sync the database
  * Create apps
  * Change settings in project to inlude apps
  * Create a model
  * Make migrations to sync the model
  * Create superuser/admin
  * Create views via view.py
  * Link urls
  * Create templates
  * Test

* Can you explain the primary differences between Django and Django REST framework?
  * Django vanilla is quite robust and allows for more overall customization while Django REST focuses on building APIs

## Readings

* [Beginner's Guide to Docker](https://wsvincent.com/beginners-guide-to-docker/)
* [Django for APIs - Library Website](https://djangoforapis.com/library-website-and-api/)
* [Beginner's Guide to Django REST Framework](https://learndjango.com/tutorials/official-django-rest-framework-tutorial-beginners)