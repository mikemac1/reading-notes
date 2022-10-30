# Reading Assignment 07

## Why This Matters

Having an understanding for modeling makes it easier for the developer to ensure they understand the problem they are creating a solution for and provides a communication medium in explaning to others what the code does. Also understanding why we don't want to use tables makes us a better developer in general for not using elements for other than their stated purpose.

## Questions To Answer

### Explain why we need domain modeling

Domain modeling has two significant impacts to why it is needed when programming. First it helps the programmer to be able to provide a conceptual model in organizing the functions the program will have and how it solves a problem. It centers on the programmer being able to display in a pictorial view the inputs, the process, and the outputs the program is going to have. The second impact is being able to communicate how a problem is solved to those that do not have a programming background. An effective pictorial can immediately show a problem is solved and gain consensus on how a problem is solved.

### Why should tables not be used for page layouts?

Tables should only be used to maintain data across two axis for showing data in columns or tables that display relationships. However some coders utilize tables for page layouts and styles when CSS & JS should handle how a page looks and acts. Three reasons for not using tables as a CSS measure are the reduction of accessibility for the visually impaired, tables do not give the ability to be responsive by default, and tables create a very convoluted look and makes it very difficult to maintain & read thru the code of the table.

### List and describe 3 different semantic HTML elements used in an HTML `<table>`

`tr`: is the table row element and shows a row of cells in a table.
`td`: is the table data cell element which shows a cell of a table and contains some text or data.
`th`: is the table header element which shows a cell as the header for a row or column of table cells.

### What is a constructor and what are some advantages to using it?

Constructors allow for creating a "model" of an object with the same properties and then can be reutilized to create several copies with different values. The biggest advantage is reusability to have a set of code than can do the same function with keywords like `this` or `new` to be relative to the specific object used. Also it makes it easier for different people to maintain the code as there is only one set of code copied for various objects.

### How does the term `this` differ when used in an object literal versus when used in a constructor?

From a function standpoint `this` points to the object name as it exists for the current object in object literal. While used in a constructor the functionality remains the same, however the constructor lets multiple instances of that object exist for the developer and the change made to the original object doesn't change the other objects created.

### Explain prototypes and inheritance via an analogy from your previous work experience

NOTE: This is a very common front end developer interview question
> In JavaScript, an object can inherit properties of another object. The object from where the properties are inherited is called the prototype. In short, objects can inherit properties from other objects — the prototypes.
> [JavaScript Prototypes and Inheritance – and Why They Say Everything in JS is an Object](https://www.freecodecamp.org/news/prototypes-and-inheritance-in-javascript/#:~:text=In%20JavaScript%2C%20an%20object%20can,from%20other%20objects%20%E2%80%94%20the%20prototypes.)

The easiest way to see the difference between inheritance and prototype is when a car is built. Originally a prototype is built that will exhibit the properties and design specifications for the cars that follow on the assembly line. When you buy that brand new car it inherited the properties from that original prototype when it was designed.

## Things I Want To Know More About

I'm working on trying to find an alternative source of info like W3 to substitute for MDN docs with regards to JS and the DOM.

## Sources Utilized

[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

[HTML table basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

[`<tr>`: The Table Row element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tr)

[`<th>`:The Table Header element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/th)

[`<td>`: The Table Data Cell element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/td)

[Introducing constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

[What is a constructor in JavaScript](https://www.educative.io/answers/what-is-a-constructor-in-javascript)

[A Beginner's Guide to JavaScript's Prototype](https://ui.dev/beginners-guide-to-javascript-prototype)

[HTML table advanced features and accessibility](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)
