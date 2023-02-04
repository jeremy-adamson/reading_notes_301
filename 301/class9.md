# Functional Programming

## Functional Programming Concepts

* What is functional programming?
  * A style of programming that treates computation as the evaluation of mathematical functions and avoids changeing-state and mutable data.
* What is a pure function and how do we know if something is a pure function?
  * In short, all pertinent information is either contained within or passed into the function as parameters.
* What are the benefits of a pure function?
  * It's easier to test since the end result will not change unless if the arguments passed into the function change.
* What is immutability?
  * Basically const.  Something that cannot be changed once it has already been created.
* What is Referential Transparency?
  * Pure function with immutability. Or basically, don't change things that are passed by reference which is a perfectly okay thing to do in C++ and working on solo projects but can have wonky consequences when other people are trying to code using your own code.

## Node JS for Beginners

* What is a module?
  * A module is basically a library but only covers one piece of functionality instead of multiple. Also unlike traditional libraries, all containing code and functions are private be default unless specified otherwise via an export line.
* What does the word 'require' do?
  * It's kinda like import except import is only for libraries and require specifies a particular entry point
* How do we bring another module into the file we are working in?
  * Set a variable to contain the result of the require function.
* What do we have to do to make a module available?
  * Use an export line at the end of the module.

## Readings

* [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)
* [Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)
