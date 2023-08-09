# Pythonisms

## Reading Questions

* What are dunder methods in Python and how do they allow for the customization of built-in behavior in classes? Provide an example of a common dunder method and its purpose.

  * Dunder methods are used to override build in methods when they might be used inappropriatedly by default typically for class methods. For example if I were to make a new class using a new number set (via group/ring theory) and if I were to redefine what addition would be between two objects of that class I may incorporate a __add__ method

* Explain the concept of an iterator in Python. How do you create a custom iterator using the iter() and next() method, and why are they important for enabling iteration in a class?

  * An iterator in Python allows 'for each' or 'for in' operations to work with developer defined classes which my not be able to have built in iterators. __iter__ defines that an object will be iterable while __next__ indicates how the object will be interated over.

* What is a generator in Python and how does it different from a regular function? Illustrate your answer with an example of a generator function using the 'yield' keyword.

  * A generator in Python uses yield instead of a return statement at the end. In short it sends back the current value at yield but is intended to be called again (somewhat like next) and will return the next value when called upon until termination (end of the loop/list).

* Define decorators in Python and explain their primary use case. How can you create and apply a custom decorator to a function or method? Provide a simple example to demonstrate this concept.

  * A decorator is a pattern for calling a fuction within an inner wrapper function incorporating an additional nested function within. The wrapper itself is intended to modify the behavior of the innermost function without actually changing that function itself.

## Readings

* [Dunder Methods](https://dbader.org/blog/python-dunder-methods)
* [Iterators](https://dbader.org/blog/python-iterators)
* [Generators](https://dbader.org/blog/python-generators)
* [What are Generators](https://realpython.com/lessons/what-are-python-generators/)
* [Decorators](https://realpython.com/primer-on-python-decorators/)
