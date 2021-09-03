1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here

let getPercentage = function(marks, total) {
  return (marks * 100) / total;
}
//and
let getPercentage = (marks, total) => {
  return (marks * 100) / total;
}
// and
let getPercentage = (marks, total) => (marks * 100) / total;

```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer

let getPercentage = function(marks, total) {
  return (marks * 100) / total;
}
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

let percentage = function(marks, total) {
  return (marks * 100) / total;
},
// or
let percentage =(marks, total) => {
  return (marks * 100) / total;
}


```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

let percentage = (marks, total) => {
  return (marks * 100) / total;
}
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

let percentage = (marks, total) => (marks * 100) / total;

```

```js
let percentage = (marks, total) => (marks * 100) / total;
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

Because functions are value and they can be assigned,copied and decleared in any place that's why function definition is an expression. exp-

let add = function(a,b){
  return a+b;
}

4. Why is a function call an expression in JavaScript?
 
 Because function call has a function name and  it receive a value as parameter.

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer VALID ,Because calling the function and passing arguments.
five = add; // Answer  INVALID ,Because five is not a variable and add is not a function call.
five = five(10, 11); // Answer, Because five is not a variable and not a function also.
five = function () {
  return 'Hello';
}; // Answer  , Because five is not a variable .
```

6. What is the difference between function definition and function call? Explain with an example.
<!-- function definition - is a colletion  of steps like below--> 
function substract(a, b) {       
  return a - b;              
 }        
<!-- function call - receive value as an argument -->
 substract() ; //(4,3) 

7. What is the similarities between function definition and function call?

  Both are present with function name.

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid or invalid // INVALID Because no accepting any parameter and assigning a value.
```

9. What is higher order function explain with an example.

A higher order function is a function that accepts a function as an parameter or return a function.

10. Explain what is callback function. Why you can pass a function inside a function?

callback function is a function that is passed as an argument in  another function.
