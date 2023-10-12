1.What does thread of execution means in JavaScript?
Ans: JavaScript goes through code line by line and executes it, known as a thread of execution. That is, it threads its way down the code, top to bottom, and executes each line. JavaScript is synchronous, which means it moves to the next line only when the execution of the current line is completed.
2. Where the JavaScript code gets executed?
Ans: When the JavaScript engine scans a script file, it makes an environment called the Execution Context that handles the entire transformation and execution of the code. During the context runtime, the parser parses the source code and allocates memory for the variables and functions.
3. What does context means in Global Execution Context?
Ans: The global execution context is created when a JavaScript script first starts to run, and it represents the global scope in JavaScript. A function execution context is created whenever a function is called, representing the function's local scope.
4. When do you create a global execution context.
Ans: The global execution context is created when a JavaScript script first starts to run, and it represents the global scope in JavaScript. A function execution context is created whenever a function is called, representing the function's local scope.
5. Execution context consists of what all things?
Ans: JavaScript is a single-threaded interpreted language. Every browser has its own JavaScript engine. Google Chrome has the V8 engine, Mozilla Firefox has SpiderMonkey, and so on. They all are used for the same goal, because the browsers cannot directly understand JavaScript code.
6. What are the different types of execution context?
Ans: There are two types of execution contexts: global and function. The global execution context is created when a JavaScript script first starts to run, and it represents the global scope in JavaScript. A function execution context is created whenever a function is called, representing the function's local scope.
7. When global and function execution context gets created?
Ans: Global execution context get created whenever theere is need to execute a code snippet or a program, it gets created just for one time whereas function execution context gets created multiple times depending upon the number of function to be executed in the given code snippet. whenever there is a need to execute a function, javascript engine creates a new function ecxecution context.
8. Function execution gets created during function execution or while declaring a function.
Ans: It gets created during the execution of function and not when it is defined
9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)