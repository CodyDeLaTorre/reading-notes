# Class 10 Reading Notes

## JavaScript Call Stack

1. What is a ‘call’?
2. How many ‘calls’ can happen at once? One
3. What does LIFO mean? Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.
4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

~~~
function firstFunction(){
  console.log("Hello from firstFunction");
}

function secondFunction(){
  firstFunction();
  console.log("The end from secondFunction");
}

secondFunction();
~~~

5. What causes a Stack Overflow? A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.

## JS Error Messages

1. What is a ‘reference error’? This is as simple as when you try to use a variable that is not yet declared you get this type of errors.
2. What is a ‘syntax error’? This occurs when you have something that cannot be parsed in terms of syntax.
3. What is a ‘range error’? Trying to manipulate objects or arrays with invalid lengths.
4. What is a ‘type error’? These types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible.
5. What is a breakpoint? Breackpoint allows you to debug code and shows you if the line you selected was run you will be able to see what has happened before that point and you can try and evaluate the next lines to check if everything is outputting what you are expecting.
6. What does the word ‘debugger’ do in your code? it adds a breakpoint in your code

---

### Resources

[JS Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)

[JS Error Msgs](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

---

[Back to Home](../README.md)
