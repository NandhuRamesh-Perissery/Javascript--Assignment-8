## 1. Write short notes on the below with code examples

## while loop -

The while loop is used to repeat a section of code an unknown number of times until a specific condition is met.

```JS

let i = 1
  while(i<5){
    console.log(i);
    i++
  }

```

## do-while loop - 

The do while loop checks the condition at the end of the loop.

```js

let count =30
do{
  console.log(count);
  count++
}while(count<5)

```

## for loop -

A for loop is a control flow statement for specifying iteration, which allows code to be executed repeatedly. 

```js
let i = 1
for (i=0;i<5;i++){
    console.log(i);

}

```

## for in -

A for-in loop is a control structure that allows you to iterate over the enumerable properties of an object. 

```js
let symbols ={
    yt:"youtube",
    ig:"instagram",
    in:"linkedIn",
    fb:"facebook"

}
for(i in symbols){
    console.log(i);
    console.log(symbols[i]);
       
}

```

## for Of loop -

A for Of loop operates on the values sourced from an iterable one by one in sequential order.

```js

let arr=[1,2,3,4,5]
for(i of arr){
    console.log(i);
    
}

```

## 2. Explain the scope in Javascript ?

Ans : 


Block scope -
           Earlier JavaScript had only Global Scope and Function Scope. let and const are the two new important keywords that were introduced by the ES6 and these two keywords provide Block Scope in JavaScript. ECMAScript (ES6) 2015 was the second major revision to JavaScript. Variables that are declared inside a { } block cannot be accessed from outside the block.

Function scope -
            JavaScript has function scope and each function creates a new scope. Variables defined inside a function are not accessible from outside the function and variables declared with var, let and const are quite similar when declared inside a function.

Local scope -
           Variables declared inside a function become local to the function. Local variables are created when a function starts and deleted when the function is executed. Local variables have Function Scope which means that they can only be accessed from within the function.

Global scope -
           Variables declared Globally (outside of any function) have Global Scope and Global variables can be accessed from anywhere in a program. Similar to function scope variables declared with var, let and const are quite similar when declared outside a block.


## 3. What is a callback ?

Ans : 

     A JavaScript callback is a function which is to be executed after another function has finished execution. 


## 4. Explain context in JavaScript ?

Ans :

     In JavaScript, “context” refers to an object. Within an object, the keyword “this” refers to that object (i.e. “self”), and provides an interface to the properties and methods that are members of that object. When a function is executed, the keyword “this” refers to the object that the function is executed in.


## 5. What is hoisting in JavaScript ?

Ans :

     In JavaScript, hoisting refers to the built-in behavior of the language through which declarations of functions, variables, and classes are moved to the top of their scope – all before code execution. In turn, this allows us to use functions, variables, and classes before they are declared.


## 6. Explain lexical scope ?

Ans :

     The ability of a function scope to access variables from the parent scope. When there is lexical scope, the innermost, inner and outermost functions may access all variables from their parent scopes all the way up to the global scope.



## 7. What is scope chaining ?

Ans :

     Scope Chain means that one variable has a scope (it may be global or local/function or block scope) is used by another variable or function having another scope (may be global or local/function or block scope). 


## 8. Explain closure ?

Ans :

     It is the combination of a function and its lexical environment with the function is declared.

## 9. What is the difference between undefined and not defined in javascript ?

Ans :

    The primary distinction between undefined and not defined is: A variable that has been declared but not assigned a value is undefined . A variable that has not been declared at all is not defined .


## 10. Explain spread and rest operator ?

Ans :

    The spread operator, denoted by three consecutive dots (...), is primarily used for expanding iterables like arrays into individual elements. This operator allows us to efficiently merge, copy, or pass array elements to functions without explicitly iterating through them.

    The rest operator,rest operator allows to copy part of an exisiting array into an another array.


## 11. Explain ‘this’ keyword in Javascript ?

Ans :

     This keyword is used to access the properties inside an object.

