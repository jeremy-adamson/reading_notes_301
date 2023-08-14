# API Deployment

## Questions

* What are the key principles to follow when organizing and configuring Django settings for a project according to the "Django Settings Best Practices" reading?
  * Keep settings in environment variables
  * Write default values for production configuration
  * Don't hardcode sensitive settings and don't put them in VCS
  * Split settings into groups between Django, third-party, project
  * Follow naming conventions for custom settings

* How does the White Noise library contribute to the efficient serving of static files in a Django application and what are the steps to integrate it into a project?
  * White Noise compresses the static files and allows for caching so that files which have already been downloaded won't need to be resent.
  * The steps to include it are:
    * pip install whitenoise
    * Changing settings.py to include whitenoise.middleware.WhiteNoiseMiddleware in MIDDLEWARE
    * Add in STATICFILES_STORAGE = "whitenoise.storage.CompressedManifestStaticFilesStorage"

* What is the purpose of Cross-Origin Resource Sharing (CORS) in web applications and how can it be implemented and configured in a Django project to control access to resources?
  * CORS is intended to allow web pages to request additional information from other pages (or locations) and incorporates security features to ensure that these requests play by the rules (are not malicious)
  * It can be implemented by instealling django-cors-headers
  * Changing settings.py wo include corsheaders.middleware.CorsMiddleware in MIDDLEWARE
  * Changing or adding CORS_ALLOWED_ORIGINS to include the domains which are allowed to access the site 

## Readings

* [Django Settings Best Practices](https://djangostars.com/blog/configuring-django-settings-best-practices/)
* [White Noise](http://whitenoise.evans.io/en/stable/)
* [CORS](https://en.m.wikipedia.org/wiki/Cross-origin_resource_sharing)