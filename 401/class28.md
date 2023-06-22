# Django CRID and Forms

## Reading Questions

* How do Django Forms facilitate user input handling and what are some key components of creating a form using the Django framework?
  * Django Forms takes care of displaying the default form for the first time, is able to receive data from a submit request and "binds" it (aka stores the information available to be read), validates the bound data to see if it fits the input parameters, if it isn't then the form is displayed to the user with valid fields pre-filled, if all the data is valid then the information is allowed to be used for an action.
  * The key components for a form include
    * Declaration
    * Definine the fields
    * Validation parameters
    * URL configuration (how it is to be used)

* Explain the purpose of Django Templates in web development and describe how template inheritance can be utilized to improve code reusability and maintainability.
  * Inheritance allows for code to be re-used in general without having it to be re-written however the main benefit about inheritance in this case is having a single source of truth for the code. If any changes need to be made in the future and IF the templates are using inheritance properly, then only one class will need to be changed instead of looking for the code in numerous different places. This also allows for ease of updates.

* Describe the function of Django Views in handling HTTP requests and outline the differences between function-based views and class-based views.
  * The main differences between function-based views and class-based views is the function based are more specific to the individual task being handled. Class-based views can be inherited, allow for modifier tags, bring in smaller classes to interact with the chosen parent class, and overall allow for more flexibility instead of being locked into hard-coding anything that is slightly different from the main function.

## Readings

* [Django Forms](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Forms)
* [Django Templates](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Home_page)
* [Django Views](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Generic_views)
