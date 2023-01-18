# React and Forms

## React Docs - Forms

* What is a 'Controlled Component'?
  * An in put form element whose value is controlled by the component's state.
* Would we wait to store the user's responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why?
  * I am uncertain as it would probably depend upon how the information is being used. I would guess that updating the responses as soon as the user enters them would be valuable for auto-fill or filters on a list without having to click the submit button.  However for a regular form where you want the user to completely finish their input, then it would be best to wait until the user clicks the submit button.
* How do we target what the user is entering if we have an event handler on an input field?
  * By using `onChange` as a separate argument to call a function to specifically change state.

## The Conditional Ternary Operator Explained

* Why would we use a ternary operator?
  * Shorthand for a simple boolean comparison
* Reqrite the following statement using a ternary statement:
  * `x===y ? console.log(true):console.log(false);`

## Bookmarks

* [React Docs - Forms](https://reactjs.org/docs/forms.html)
* [The Conditional (Ternary) Operator](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)
* [React Bootstrap - Forms](https://react-bootstrap.github.io/forms/overview/)
* [React Docs - conditional rendering](https://reactjs.org/docs/conditional-rendering.html)