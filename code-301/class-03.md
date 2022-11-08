# Reading Assignment 03 - Code 301

## Why This Matters

## What does `.map()` return?

The map method receives a function as a parameter. Then it applies it on each element and returns an entirely new array populated with the results of calling the provided function. This means that it returns a new array that contains an image of each element of the array. It will always return the same number of items.

## If I want to loop through an array and display each value in JSX, how do I do that in React?

Multiple components can be built from an array once it has been looped thru and included them in JSX using curly braces {}.

## Each list item needs a unique ____

Each list item needs a unique **string**.

## What is the purpose of a key

Keys help React identify which items have changed, are added, or are removed. Strings are utilized for keys and should be given to the elements inside the array to give the elements a stable identity. It is **NOT** recommended to use indexes in place of keys if the order of items may change. This can negatively impact performance and may cause issues with component state.

## What is the spread operator?

The spread operator (`...`) is a syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

## List 4 things that the spread operator can do

It can copy an array, combine arrays, allows the use of `Math` functions, allows using an array as arguments, adding an item to a list, adding an array to state in React, and combining objects.

## Give an example of using the spread operator to combine two arrays

The spread operator can merge 2 or more arrays by using the following syntax
`[...array1, ...array2]`

This methid is permanent because the merge result is stored in a new array.

## Give an example of using the spread operator to add a new item to an array

Using the spread operator to add a new item to an array can look like this
`puppiesArray.push(...newPuppy);`

## Give an example of using the spread operator to combine two objects into one

Here is an example of using the spread operator to combine two objects into one:

`let person = {name: 'Mike', age: 53, hair: 'brown };`
`let woodWorker = {favoriteTool: 'miter saw' favoriteBrand: 'Dewalt' };`

`let newCoder = {...person, ...woodWorker};`

## In the video, what is the first step that the developer does to pass functions between components?

## In your own words, what does the `increment` function do?

## How can you pass a method from a parent component into a child component?

## How does the child component invoke a method that was passed to it from a parent component?

## Things I want to know more about

## Sources To Cite

- [How to Use the Spread Operator (…) in JavaScript](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

- [React - How to Pass Functions between Components - Episode 22](https://www.youtube.com/watch?v=c05OL7XbwXU)

- [Tutorial: Intro to React](https://reactjs.org/tutorial/tutorial.html)

- [Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)

- [Lists and Keys](https://reactjs.org/docs/lists-and-keys.html)

- [The Differences Between forEach() and map() that Every Developer Should Know](https://www.freecodecamp.org/news/4-main-differences-between-foreach-and-map/)
