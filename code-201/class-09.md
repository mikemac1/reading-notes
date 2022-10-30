# Reading Assignment 09

## Why This Matters

When it comes to gaining insight to a user, forms are definitely a difference maker. To be able to collect data from a user from getting a grocery order to applying for college, the need to go anywhere has been reduced greatly. It is technologies like forms that can have a great deal of impact if written correctly.

## Questions To Answer

### Why are forms so important in web development?

Users main interaction with a web site or application is thru web forms. It allows them to enter data, communicate with an organization, company or person, and take action like submit applications for college or purchase insurance. Web forms give the user the power to accomplish tasks that usually required leaving our homes.

### When designing a form, what are some key things to keep in mind when it comes to user experience?

Designing a form starts with an important concept used for so many different projects, keep it simple. Use only the data that is absolutely required for a user to enter.  The best way to have an excellent form can start with creating a basic wireframe that can show the developer what the form will look like. Again, remembering the keep it simple design means having a form that will capture what you need and not overload the user.

### List 5 form elements and explain their importance

`<form>`: element tells HTML that its contents will be a form and associated attributes will detail its behavior. The reason why we want to use `form` is many assistive technologies and browser plugins can utilize the `<form>` element and make the form easier to use for those with visual impairments.
`<fieldset>`: element is used to create a groups of form's inputs that share the same purpose, for the styling and semantic purposes. It also supports most assistive reading technologies but as the ability to see what is selected. For instance if a specific radio button is selected, the assistive reading technology will describe what is selected and what is not.
 `<legend>`: element uses text to formally describe the purpose of the `<fieldset>`. Again having the legend, like the previous two elements provides a clear indication with the use of reading technologies to assist those visually impaired users.
`<label>`: element is not only the formal way to define a label for an input on a form but of all the elements is considered the most important element in building accessible forms. The screen reader will speak a form element's label along with any related instructions.
`<input>`: element allows the developer to gain data from the user within a web-based form. `input` has a diverse assortment of types of inputs that are available, depending on the developer's desire. The `input` element has a large  number of combinations of not only types but attributes that give an arsenal of functionality.

### How would you describe events to a non-technical friend?

Look at events like standing on a street corner with a four-way stop. People wait for the green hand to let them cross the street and when the red hand begins to flash they know they have limited time to finish crossing. Cars sit at the red light and await for it to turn green. While cars race to the intersection when they see the light turns yellow with the hope of making it across the intersection.  Each of these is an event that signals to the pedestrians and the cars what is allowed to happen or what is already happening.

### When using the addEventListener() method, what 2 arguments will you need to provide?

The button's `addEventListener()` method, passing in:

- the string 'click', to indicate to listen to the click event
- a function to call when the event happens such as setting the page's background-color to be set to a new color.

### Describe the event object. Why is the target within the event object useful?

The event object is passed to event handlers to provide extra features and information. The target part of the event object is pointing at the element the event is to occur on. For example, a random font color on a paragraph of text could be changed.

## What is the difference between event bubbling and event capturing?

> Event bubbling and event capture are terms that are phases in how a browser handles events which are pointing at nested elements. Event bubbling is when an event happens on an element, it first runs the handlers on it, then on its parent, then all the way up on other ancestors.  The other step in event processing is called event capturing and is rarely used in real code. However sometimes it can be useful as the capturing phase goes down to the element with two possible values. Either it is false (default) where the handler is set on the bubbling phase or its true where the handler is set on the capturing phase.
> [Bubbling and capturing](https://javascript.info/bubbling-and-capturing)

## Sources Utilized

[Web forms — Working with user data](https://developer.mozilla.org/en-US/docs/Learn/Forms)

[Your first form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)

[How to structure a web form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)

[JavaScript — Dynamic client-side scripting](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

[Introduction to events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

[The HTML5 input types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)

[Event reference](https://developer.mozilla.org/en-US/docs/Web/Events)

[Bubbling and capturing](https://javascript.info/bubbling-and-capturing)
