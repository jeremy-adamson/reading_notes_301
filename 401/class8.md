# Ten Thousand 3

## Reading Questions

* What is the basic syntax of Python list comprehension, and how does it differ from using a for loop to create a list? Provide an example of a list comprehension that squares the elements in a given list of integers.
  * Basic syntax:
    * expression/function for element in list
  * Is usually faster than a for loop
  * element ** 2 for element in list
* What is a decorator in Python?
  * Basically function inheritance
* Explain the concept of decorators in Python. How do they work, and what are some common use cases for them? Provide an example of a simple decorator function from the reading.
  * It just seems like decorators are very similar to class inheritance except for functions where extra bits are added onto the core function.
  * Example:
    * def my_function():
      * print("world")
    * def my_other_function():
      * def wrapper():
        * print("hello")
        * my_function()
      * return wrapper

## Readings

* [List Comprehensions](https://www.pythonforbeginners.com/basics/list-comprehensions-in-python)
* [Debugging with PySnooper]https://www.pythonpodcast.com/pysnooper-python-debugging-episode-241/)
* [Primer on Decorators](https://realpython.com/primer-on-python-decorators/)