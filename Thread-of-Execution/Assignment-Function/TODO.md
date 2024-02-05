1. Convert the function below into different forms of function expression.
   function percentage(marks, total) {
   return (marks \* 100) / total;
   }

```js
     let percentage = function (marks, total) {
     return (marks \* 100) / total;
     }
     let percentage = (marks, total) => {
     return (marks \* 100) / total;
     }
```

2. Write Function Declaration or Function Expression next to the function.

```js
 - Function declaration:
     let percentage = function (marks, total) {
     return (marks \* 100) / total;
     }
 - Function Expression:
     let percentage = function (marks, total) {
     return (marks \* 100) / total;
     }
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

- `Function definition an expression in javascript because it evaluates to a value which takes parameter as a function and passing in hof as a function`

```js
let add = function (a, b) {
  return a + b;
};
console.log(add(1, 2)); //3
```

4. Why is a function call an expression in JavaScript?

- `a function call is an expression because it results in a value. When you call a function, it returns a value, which can be used or manipulated further in your code`

```js
function add(a, b) {
  return a + b;
}
let result = add(12, 8);
console.log(result); //20
```

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); //VALID
five = add; // INVALID bcz five is not defined
five = five(10, 11); // INVALID bcz five is not defined
five = function () {
  return 'Hello';
}; //   "VALID"
```

6. What is the difference between function definition and function call? Explain with an example.

- `function definition means defining a function and funtion calling call the function`

```js
// function definition
function multiply(a, b) {
  return a * b;
}
//function calling
multiply(1, 2); //2
```

7. What is the similarities between function definition and function call? Explain with an example.

- `the similarities between function definition and function call are that the both have same name and function definition takes parameters function call passes the paranthesis`

```js
// function definition
function subtract(a, b) {
  return a - b;
}
//function calling
subtract(4, 2); //2
```

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid  as function is type of object so we can treat it as an object
```

9. What is higher order function explain with an example.

- `HOF is the function whuch contain one or more function and also take function as an parameter`

```js
function greeting(greet = 'hello') {
  return (name = '') => {
    return `${greet} ${name}`;
  };
}
greeting(); //(name = '') => {return `${greet} ${name}`}
greeting()(); //('hello ');
greeting('hey')('sunny'); //'hey sunny'
```

10. Explain what is callback function. Why you can pass a function inside a function?

- `callback function is the function which passed as a parameter to other function`

```js
function solve(cb) {
  return cb;
}
function add(a, b) {
  return a + b;
}
solve(add(10, 10)); //20
```
