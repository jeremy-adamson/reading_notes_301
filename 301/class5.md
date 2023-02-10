# React Revisited

## React Docs

* What is the `single responsibility principle` and how does it apply to components?
  * A component should only do one thing.
* What does it mean to build a 'static' version of your application?
  * A static version of the code is one where elemtents or variables normally meant for changing or external input are instead hard-coded to test if the base code works before testing if interactivity works.
* Once you have a static application, what do you need to add?
  * Interactivity with minimal set of state
* What are the three questions you can ask or determine if something is state?
  * Is it passed in from a parent via props?
  * Does it remain unchanged over time?
  * Can you comput it based on any other information stored in state or props?
* How can you identify where state needs to live?
  * Identify every component that render something based on that state
  * Find a common owner component
  * Either the common owner or another component higher up in the heirarchy should own the state.
  * If nothing else makes sense, make a separate component for storing the state

## Higher-Order Functions

* What is a "higher-order function"?
  * Functions that operate on other functions
* Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?
  * Line 2 is and arrow function which can then be assigned at the place of invocation where n is now a fixed value dependent on the initial greaterThan parameter.
* Explain how either `map` or `reduce` operates, with regards to higher-order functions.
  * Map creates a second array and fills it with the transform of each individual element of the original array and then returns the second array

## Reading

* [React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
* [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)
