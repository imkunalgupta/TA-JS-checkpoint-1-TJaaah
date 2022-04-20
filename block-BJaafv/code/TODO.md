1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```
:= first function has return statement and second function do not have return statement. so value of first fuction can be stored in any variable.

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
:= first will give a value which is provied to it with addition. second will give undefined value.

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
:= As we have given only two parameter to the function then in argument function take first two value so the result will be 36.

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
:= As first function has a return statement it can be store.

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

```js
function sayHello(name) {
  return name ;
  }

sayHello("Hello Arya");
```

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage(); // 'Hello John'
```

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // "John"

showMessage(); // "Hello John"

alert(userName); // "John"
```

8. What is a Anonymous Function give example of three functions.
An anonymous function is a function without a name! Anonymous functions are commonly assigned to a variable name or used as a callback function.
 
for example :- 

let add = function(a, b){
  return a + b;
 }


let multiply = function(a, b){
  return a * b;
 }


let substract = function(a, b){
  return a - b;
 }

9. Can function declaration be a Anonymous Function? Explain

No

Function declarations have a variable name; while anonymous functions do not. The main difference is that a function declaration is 'declared'. In other words, it has been assigned to a variable and can be later referenced with said variable.


10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
userName
fullName
getMaxNumber
calculateBMI
checkEqual