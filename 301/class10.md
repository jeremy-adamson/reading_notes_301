# In Memory Storage

## Understanding the JavaScript Call Stack

* What is a 'call'?
  * A function invocation
* How many 'calls' can happen at once?
  * One, if it's synchronous.
* What does LIFO mean?
  * Last In First Out - Stack (instead of a queue)
* Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
* What causes a Stack Overflow?
  * When the stack fills up with function calls (typically through recursion)

## JavaScript Error Messages

* What is a 'reference error'?
  * If memory has not been allocated for the variable or object being called
* What is a 'syntax error'?
  * Basically a coding 'spelling error'
* What is a 'range error'?
  * When a value is out of the range that is intended aka shoving 100000 into an unsigned short (range of 65000-ish)
* What is a 'type error'?
  * Performing an operation on a data type which is not valid for that data type
* What is a breakpoint?
  * A stopping point in the program inserted for the purposed of debugging
* What does the word 'debugger' do in your code?
  * Stops the program at that point and calls the debugging function

## Readings

* [Understanding the JavaScript Call Stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)
* [JavaScript Error Messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)
* [JavaScript error reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)
