# Reading Assignment 05 - Code 301

## Why This Matters

Understanding the "requirements" for an app gives the team of developers a clear goal of what to work to. Building with creeping requirements makes the target a moving goal.

## What is the `single responsibility principle` and how does it apply to components?

The single responsibility principle is when a component should only do one thing and if its responsibility or funcationality ends up growing, it should be broken up into smaller subcomponents.

## What does it mean to build a ‘static’ version of your application?

Building a static version of an app is to build a version that takes data models and renders the UI but has no interactivity.

## Once you have a static application, what do you need to add?

State needs to be added.

## What are the three questions you can ask to determine if something is state?

- Is it passed in from a parent via props? If so, it probably isn’t state.
- Does it remain unchanged over time? If so, it probably isn’t state.
- Can you compute it based on any other state or props in your component? If so, it isn’t state.

## How can you identify where state needs to live?

For each piece of state in the application:

- Identify every component that renders something based on that state.
- Find a common owner component (a single component above all the components that need the state in the hierarchy).
- Either the common owner or another component higher up in the hierarchy should own the state.
- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

## What is a “higher-order function”?

Higher-order functions are functions that operate on other functions, either by taking them as arguments or by returning them.

## Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?

  `return m => m > n;`
This means when m is greater than n, return m.

## Explain how either `map` or `reduce` operates, with regards to higher-order functions

The map method transforms an array by applying a function to all of its elements and building a new array from the returned values. It is using its function to search thru an array and apply a given function or condition to return.

## Things I want to know more about

Higher order functions "feels" like callback functions but I am not sure?

## Sources To Cite

- [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

- [Higher-order functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)
