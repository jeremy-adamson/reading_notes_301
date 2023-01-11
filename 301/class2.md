# State and Props

## React lifecycle

* Based off the diagram, what happens first, in the 'render' or the 'componentDidMount'?
  * `render` occurs before `componentDidMount`
* What is the very first thing to happen in the lifecycle of React?
  * `constructor` is the first thing to happen in the lifecycle of React.  Have to first allocate the space for the object after all.
* Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`
  * `constructor`, `render`, `componentDidMount`, `React Updates`, `componentWillUnmount`
  * Pretty sure `render` should occur twice in the above, once during the mounting and then after each `React Update`
* What does `componentDidMount` do?
  * Not too sure but it is called directly after a component is mounted. It can be used to trigger loading data remotely and any initialization that requires DOM nodes can go here.

## React State vs. Props

* What types of things can you pass in the props?
  * Anything that can be a function argument (typically initial settings)
* What is the big differnce between props and state?
  * Props are static while inside a child component and cannot be changed while state is local to that component and the component re-renders whenever state is changed
* When do we re-render our application?
  * Whenever state changes
* What are some examples of things that we could store in state?
  * Anything that is going to change either with user input (button presses) or automated (like a clock).

## Reading

* [React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)
* [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)
* [React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)
* [React Docs - handling events](https://reactjs.org/docs/handling-events.html)
* [React Tutorial through ‘Developer Tools’](https://reactjs.org/tutorial/tutorial.html)
* [React Bootstrap Documentation](https://react-bootstrap.github.io/)
* [Boootstrap Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)
* [Bootstrap Shuffle - a class “sandbox”](https://bootstrapshuffle.com/classes)
* [Netlify](https://www.netlify.com/)