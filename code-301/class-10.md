# Reading Assignment 10 - Code 301

## Why This Matters

Having an understanding for not only what type errors are occurring but where to help find them is key.

## What is a ‘call’?

A call is a function invocation.

## How many ‘calls’ can happen at once?

A call stack is single, function(s) execution is done one at a time, from top to bottom which means the call stack is synchronous.

## What does LIFO mean?

A call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack

As an example:

function firstFunction(){
  console.log('First function run');
}

function secondFunction(){
  firstFunction();
  console.log('Second function run');
}

function thirdFunction(){
  secondFunction();
  console.log('Third function run');
}

thirdFunction();

This will results in the following to be printed:
First function run
Second function run
Third function run

## What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

## What is a ‘reference error’?

A reference error is when you try to use a variable that is not yet declared you get this type os errors.

## What is a ‘syntax error’?

Syntax errors occur when you have something that cannot be parsed in terms of syntax

## What is a ‘range error’?

Range errors are when trying to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.  An example is an array for instance cannot have a negative length.

## What is a ‘type error’?

Type errors show types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

## What is a breakpoint?

The point where the developer can find the error or issue from using a debugger or console.log.

## What does the word ‘debugger’ do in your code?

The debugger statement invokes any available debugging functionality, such as setting a breakpoint. If no debugging functionality is available, this statement has no effect.

## Things I want to know more about

Being able to understand how to interpret the different errors to be able to hone in on the cause and quickly resolve is going to take time & experience I know but need to take action.

## Sources To Cite

- [The JavaScript Call Stack - What It Is and Why It's Necessary](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)

- [JavaScript error messages && debugging](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

- [JavaScript error reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)
