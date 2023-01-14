# Passing Functions as Props

## Lists and Keys

* What does `.map()` return?
  * `.map()` returns the original array where each element has been modified by the inner function
* If I want to loop through an array and display each value in JSX, how do I do that in React?
  * By wrapping the mapped variable in curly braces
* Each list item needs a unique___
  * Key
* What is the purpose of a key?
  * To give all of the elements a unique identity (somewhat similar how index is a unique identifier for which slot information is stored, minus address references and the fact that the identifier is on a slot instead of the data stored within)

## The Spread Operator

* What is the spread operator?
  * `...`
* List 4 things that the spread operator can do.
  * Have another way of
    * adding an item to a list
    * adding to state in React
    * combining objects
    * converting NodeList to an array
* Give and example of using the spread operator to combine two arrays.
  * If `arr1` and `arr2` are arrays
    * `arr3 = [...arr1, ...arr2]`
* Give an example of using the spread operator to add a new item to an array.
  * If `arr` is the array and `ele` is the new element to add
    * `arrPlus = [...arr, ele]`
* Give an example of using the spread operator to combine two objects into one.
  * If `obj1` and `obj2` are arrays
    * `obj3 = {...obj1, ...obj2}`

## Passing Functions Between Components

* In the video, what is the first step that the developer does to pass functions between components?
  * They add the method to be referenced in the parent component
* In your own words, what does the `increment` function do?
  * It searches an array for a given name and increments the count associated with that name
* How can you pass a method form a parent component into a child component?
  * Passing the method as you would any other property to be passed to a child.  The only difference would be to change the prefix to `this.`
* How does the child component invoke a method that was passed to it from a parent component?
  * By referencing the parent method as a property of the parent component inherited in a local method

## Readings / External information

* [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)
* [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)
* [Passing Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)
* [React Tutorial through 'Declaring a Winner'](https://reactjs.org/tutorial/tutorial.html)
* [React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)
