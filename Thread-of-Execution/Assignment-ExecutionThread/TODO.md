1. What does thread of execution means in JavaScript?

```js
let name = 'yatharth';
function greeting(name = '') {
  return `hello ${name}`;
}
let message = greeting(name);
```

2. Where the JavaScript code gets executed?

```js
Ans:
// In javascript engine
```

3. What does context means in Global Execution Context?

```js
Ans:
// the place or environment where the code or function get execute
```

4. When do you create a global execution context.

```js
Ans:
// global execution context create when the code is start
```

5. Execution context consists of what all things?

```js
Ans:
// it consist a memory where all the variable and function will stored and a execution context where the code will exe
```

6. What are the different types of execution context?

```js
Ans:
// Global Execution context and funct ionExecution context
```

7. When global and function execution context gets created?

```js
Ans:
    - `Global execution context`:-
    // whenever code is executed in start then global execution context will get created.
    - `Function execution context`:-
    // whenever function is executed then function execution context will get created.
```

8. Function execution gets created during function execution or while declaring a function.

```js
Ans:
// it will created on executing the function
```

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.

```js
var user = 'yatharth';

function sayHello() {
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](Screenshot%202024-02-06%20212010.png)

```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount) {
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](Screenshot%202024-02-06%20204731.png)

```js
var age = 21;

function customeMessage(userAge) {
  if (userAge > 18) {
    return `You are an adult`;
  } else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](Screenshot%202024-02-06%20210934.png)
