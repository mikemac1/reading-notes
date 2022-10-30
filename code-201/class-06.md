# Reading Assignment 06

## Why This Matters

The DOM or Document Object Model is how today's websites load faster by speeding up tasks, and provide dynamic content with the use of object creation and manipulation by JavaScript programming.

## Questions To Answer

### How would you describe an object to a non-technical friend you grew up with?

Think of an object like a library card at the reference desk to look up a book. The card includes the title, author, publisher, the number of pages, publishing year, and location in the library. An object in JS is very similar. It contains data and has associated properties which further describes the object beyond its name. Some objects also include functions with data.

### What are some advantages to creating object literals?

An object literal in JS is also called an object initializer. It is a list of pairs with a property or key associated with a value and both are separated by a colon. One advantage of object literals is readability as it is very easy to see what constitutes the object for its pairs of property and value. Another advantage is it gives the object to have the ability to hold not just data but functions as well with increases the functionality to the object.

### How do objects differ from arrays?

Arrays are objects and using a pair of brackets can be arranged by an index starting with 0. While arrays have a property:value pairs and can contain characteristics that may be data and/or functions.

### Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation

While "dot notation" is the most common way to access elements in JS, "bracket notation" allows for accessing properties with special characters in their names, and this cannot be done with dot notation.  Here is an example:

`let` elma = {
“town”: "small";
"state": "WA";
"Rusty.Tractor": "restaurant";
"Yak-burger": "attraction";
}

`elma["Rusty.Tractor"]`

This provides access to the value "restaurant". Using "dot notation" would not work.

### Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?

![Code problem to evaluate](read6a.PNG);

`this` evaluates to the object dog. When creating several object literals and instead of specifying the object name for each different object,`this` can be substituted for each function within the object and simplifies accessing the value using the same method definition.

### What is the DOM?

The DOM or Document Object Model is a way to access the HTML and CSS via JS in a coding interface. Using the DOM gives the programmer the ability to interact with the page by representing pieces of a page as objects and nodes.

### Briefly describe the relationship between the DOM and JavaScript

The DOM is the translator between the HTML page and JavaScript.  Put simply the DOM allows for object-oriented programming to manipulate the page with the use of JS.

## Things I Want To Know More About

I can see that working in the DOM is going to require a lot of practice and repetition with DOM specific commands.

## Sources Utilized

[JavaScript object basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#object_basics)

[JavaScript object Using object literal](https://dotnettutorials.net/lesson/javascript-object-using-object-literal/)

[JavaScript Dot Notation vs. Bracket Notation](https://javascript.plainenglish.iojavascript-dot-notation-vs-bracket-notation-which-to-use-when-e24117e44d71)

[Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

[What’s the Difference Between Primitive Values and Object References in JavaScript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)

[How to Solve Programming Problems](https://simpleprogrammer.com/solving-problems-breaking-it-down/)
