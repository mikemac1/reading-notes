# Reading Assignment 02 - Code 301

## Why This Matters

Having an understanding of how hooks for when certain events take place during the component lifecycle of React is important to understand. It allows the developer to control the flow of data which can have items appear, hide or change based on an event versus the way the code reads.

## Based off the diagram, what happens first, the `render` or the `componentDidMount`?

`Render` occurs before `componentDidMount`.

## What is the very first thing to happen in the lifecycle of React?

The Constructor is called right when an instance of a component is being created and inserted into the DOM and occurs prior to the of the mounting phase.

## Put the following things in the order that they happen

`Constructor`, `render`, `React updates`, `componentDidMount`, and then `componentWillUnmount`.
![React Lifecycle](https://miro.medium.com/max/828/1*6X_7HKFdQoh9eXqWgwQuvQ.png)

## What does `componentDidMount` do?

`componentDidMount()` is invoked immediately after a component is mounted. If anything needs to be loaded using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions.

## What types of things can you pass in the props?

React props can have any JavaScript value through them, including objects, arrays, and functions.

## What is the big difference between props and state?

Both hold information that influences the output of render, they are different in one important way: props get passed to the component (similar to function parameters) whereas state is managed within the component (similar to variables declared within a function).

## When do we re-render our application?

React re-renders a component when a call is made to the setState function to change the state (or the provided function from the useState hook in function components). As a result, the child components only update when the parent component's state changes with one of those functions.

## What are some examples of things that we could store in state?

In React, state can be used for storing that data which may be a string, number, or any complex object.

## Things I want to know more about

Being able to see React state and props in action will help a lot. Right now the material is all a blur as I don't really have an understanding.

## Sources To Cite

- [React: Component Lifecycle Events](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

- [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

- [When does React re-render components?](https://felixgerschau.com/react-rerender-components/)

- [State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)

- [Handling Events](https://reactjs.org/docs/handling-events.html)

- [Tutorial: Intro to React](https://reactjs.org/tutorial/tutorial.html)

- [React Bootstrap](https://react-bootstrap.github.io/)

- [React Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)

- [All Bootstrap CSS classes](https://bootstrapshuffle.com/classes)

- [Bring it all together](https://www.netlify.com/)
