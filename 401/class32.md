# Permissions and Postgresql

## Questions

* What are the key components and purpose of Django Rest Framework (DRF) permissions and how do they help in securing an API?
  * There are four general settings that can be placed in terms of permissions on either objects or API calls: IsAuthenticated,AllowAny, IsAdminUser, IsAuthenticatedOrReadOnly. The main purpose of these is to make sure that not just anyone can add, update, or delete things from the particular database that the API is accessing.

* In SQL, what is the purpose of the SELECT statement and how would you use it to retrieve all columns form a table called 'employees'?
  * The SELECT statement is the main command used to ask for information from a particular table. In this case SELECT * FROM employees would return all the records and columns in the table employees.

* Can you explain the role of DRF Generic Views and provide examples of their usage in building a RESTful API?
  * Generic views is a base class with a fair amount of REST functionality build in and can be either imported or extended as needed.

## Readings

* [DEF Permissions](https://www.django-rest-framework.org/api-guide/permissions/)
* [Review SWL Prework](https://codefellows.github.io/common_curriculum/prework/SQL)
* [Classy Django REST](http://www.cdrf.co/)
* [DRF Generic Views](https://www.django-rest-framework.org/api-guide/generic-views/)
