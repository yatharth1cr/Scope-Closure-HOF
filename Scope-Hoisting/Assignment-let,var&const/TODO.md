Find the output of the code snippets below:

```js
console.log(numA + numB);
var numA = 21,
  numB = 30;
// undefined + undefined = NaN
```

Find the output of the code snippets below:

```js
console.log(numA + numB);
numB = 30;
ERROR:- // numA is not defined
```

Find the output of the code snippets below:

```js
let numA = 21,
  numB = 30;
console.log(numA + numB);
// 21 + 30 = 51
```

Find the output of the code snippets below:

```js
console.log(sayHello());
function sayHello() {
  console.log('Hey');
}
function sayHello() {
  console.log('Hello');
}
// hello
```

Find the output of the code snippets below:

```js
let username = 'Tyrion';
sayHello();
function sayHello() {
  console.log(username);
}
// Tyrion
```

Find the output of the code snippets below:

```js
sayHello();
let username = 'Tyrion';
function sayHello() {
  console.log(username);
}
// undefined
```

Find the output of the code snippets below:

```js
let username = 'Tyrion';
sayHello();
let sayHello = () => {
  console.log(username);
};
ERROR:- // username is not defined at sayHello
```

Find the output of the code snippets below:

```js
sayHello();
let username = 'Tyrion';
let sayHello = () => {
  console.log(username);
};
ERROR:- // sayHello is not defined
```

Find the output of the code snippets below:

```js
sayHello();
var username = 'Tyrion';
let sayHello = () => {
  console.log(username);
};
ERROR:- // sayHello is not defined
```

Find the output of the code snippets below:

```js
var username = 'Tyrion';
sayHello();
let sayHello = () => {
  console.log(username);
};
ERROR:- // sayHello is not defined

```

Find the output of the code snippets below:

```js
var username = 'Tyrion';
let sayHello = () => {
  console.log(username);
  var username = 'John';
};
sayHello();
// undefined
```

Find the output of the code snippets below:

```js
var username = 'Tyrion';
let sayHello = () => {
  var username = 'John';
  console.log(username);
};
sayHello();
// John
```

Find the output of the code snippets below:

```js
var username = 'Tyrion';
let sayHello = () => {
  console.log(username);
  let username = 'John';
};
sayHello();
ERROR:- // cannot access username before initialisation
```
