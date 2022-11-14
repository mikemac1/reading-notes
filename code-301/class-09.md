# Reading Assignment 09 - Code 301

## Why This Matters

This concept appears to be about what developing software which is efficient for the machines running it as well as the prevention of bugs which may not be seen immediately but occur during certain conditions based on state.

## What is functional programming?

Functional programming (often abbreviated FP) is the process of building software by composing pure functions, avoiding shared state, mutable data, and side-effects. Functional programming is declarative rather than imperative, and application state flows through pure functions.

## What is a pure function and how do we know if something is a pure function?

A pure function is a function which given the same input, always returns the same output.  Also a pure function produces no side effects.

## What are the benefits of a pure function?

Pure functions have many beneficial properties, and form the foundation of functional programming. Pure functions are completely independent of outside state, and as such, they are immune to entire classes of bugs that have to do with shared mutable state. Their independent nature also makes them great candidates for parallel processing across many CPUs, and across entire distributed computing clusters, which makes them essential for many types of scientific and resource-intensive computing tasks. Also pure functions are also extremely independent.

## What is immutability?

Immutable data cannot change its structure or the data in it. It’s setting a value on a variable that cannot change, making that value a fact, or sort of like a source of truth.

## What is Referential transparency?

Basically, if a function consistently yields the same result for the same input, it is referentially transparent.
pure functions + immutable data = referential transparency

## What is a module?

Module in Node. js is a simple or complex functionality organized in single or multiple JavaScript files which can be reused throughout the Node. js application. Each module in Node. js has its own context, so it cannot interfere with other modules or pollute global scope.

## What does the word ‘require’ do?

Node.js follows the CommonJS module system, and the builtin require function is the easiest way to include modules that exist in separate files. The basic functionality of require is that it reads a JavaScript file, executes the file, and then proceeds to return the exports object.

## How do we bring another module into the file the we are working in?

In the `require` statement, the module name is prefixed with ./, as it’s a local file.

## What do we have to do to make a module available?

Inside the module must be implicit in making available outside the module. To do so the method `module.exports` is called to make it available in a different module.

## Things I want to know more about

I need to see pure function, immutability, and referential transparency in applied examples because it does not make sense and seems like theory to me.

## Sources To Cite

- [Concepts of Functional Programming in Javascript](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

- [Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)

- [What is require?](https://nodejs.org/en/knowledge/getting-started/what-is-require/)
