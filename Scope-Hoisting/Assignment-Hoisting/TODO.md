1. `Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.`
   Example:

```js
function hello() {
  var username = 'Arya';
}
console.log(useranme); // output
```

```js
Ans:-
  - In above code we are looking for the variable named `usename`.
  - There is no variable named `username`in the global scope.
  - The variable is inside the function named`hello`.
  - we cannot access the variable defined inside a function from outside.
  ERROR:
  (The above code will throw an error`Reference Error username is not defined`.)
```

3. `Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.`

```js
{
  const username = 'Arya';
}
console.log(useranme); // outpu
```

```js
 Ans:-
  - In above code we are looking for the variable named `usename`.
  - There is no variable named `username`in the global scope.
  - The variable is inside the block scope.
  - we cannot access the variable defined inside a block scope from outside.
  ERROR:
  (The above code will throw an error`Reference Error username is not defined`.)

```

3. `Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.`

```js
if (true) {
  let username = 'Arya';
}
console.log(useranme); // output
```

```js
Ans:-
  - In above code we are looking for the variable named `usename`.
  - There is no variable named `username`in the global scope.
  - The variable is inside the block scope.
  - we cannot access the variable defined inside a block scope from outside.
  ERROR:
  (The above code will throw an error`Reference Error username is not defined`.)
```

4. `Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.`

```js
if (true) {
  var username = 'Arya';
}
console.log(useranme); // "Arya"
```

```js
 Ans:-
  - In above code we are looking for the variable named `usename`.
  - There is variable named `username`in the block scope.
  - The variable is inside the block scope and declared with the var.
  - So, we can access the variable defined inside a block scope from outside.
  ERROR:
//   (The above code will return "Arya")

```

5. `Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.`

```js
let username = 'John';
if (true) {
  var username = 'Arya';
}
console.log(useranme); // error
```

```js
Ans:-
  - In above code we are looking for the variable named `usename`.
  - There is variable named `username`in the block scope.
  - The variable is inside the block scope and declared with the var.
  - So, we can access the variable defined inside a block scope from outside.
  ERROR:
   //(The above code will throw an error`Reference Error username is already defined`.)
```

6. `Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.`

```js
let username = 'John';
if (true) {
  let username = 'Arya';
}
console.log(useranme); // "John"
```

```js
 Ans:-
  - In above code we are looking for the variable named `usename`.
  - There is variable named `username`in the block scope and global scope.
  - The variable is inside the block scope and declared with the let.
  - So, we can't access the variable defined inside a block scope from outside.
  ERROR:
//   (The above code will return "John")

```

7. `Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.`

```js
let username = 'John';
function sayHello() {
  let username = 'Arya';
}
sayHello();
console.log(useranme); // John
```

```js
 Ans:-
  - In above code we are looking for the variable named `usename`.
  - There is variable named `username`in the function scope and global scope.
  - The variable is inside the block scope and declared with the let.
  - So, we can't access the variable defined inside a block scope from outside.
  ERROR:
//   (The above code will return "John")

```

8. `Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.`

```js
for (var i = 0; i < 10; i++) {
  console.log(i, 'First');
} // 0 1 2 3 4 5 6 7 8 9 }
console.log(i, 'Second'); // 10, second
```

```js
 Ans:-
 - in the above code we are looking for the variable i
 - we can be access the i from outside of the scope because i is declared by var.
 - so the output of first console will be
 //0,1,2,3,4,5,6,7,8,9 "First"
 - And the output of another console will be
 //10 "second"

```

9. `Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.`

```js
for (let i = 0; i < 10; i++) {
  console.log(i, 'Secont');
} // output }
console.log(i, 'Second'); // output
```

```js
 Ans:-
  - in the above code we are looking for the variable i
 - we cannot be access the i from outside of the scope because i is declared by let.
 - so the output of first console will be
 //0,1,2,3,4,5,6,7,8,9 "First"
 - And the another console will show an
 ERROR:- //(i is not defined)
```
