# Reading Assignment 04 - Code 301

## Why This Matters

Understanding how controlled components work gives the developer the ability to gain a user's history on selecting several answers including those not in the submission of a form.

## What is a ‘Controlled Component’?

Controlled components in React are those in which form data is handled by the component’s state. The data may be typed (input, textarea) or selected (checkbox, select, radiobutton, etc) by the user . When the element’s value is changed (triggered by the act of typing or selecting), it is updated accordingly.  State can then be used in the component to hold or manage the values of the elements in a form.

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why

After several times I have attempted to read this and try to understand but how one has an advantage over another but it just does not make sense.  My thought is you are running code on practically every keystroke when a response is entered and nothing stops a user from changing their mind after a response is entered to go back and update it with something else. My instict would be to store the users' responses up on submitting the form.

## How do we target what the user is entering if we have an event handler on an input field?

Again, this is a guess on my part because the reading does not make sense but I believe it is setting a `state.value` for what is entered so the value attribute can temporarily store what is written by the user.

## Why would we use a ternary operator?

Developers use the ternary operator for code in decision making as a replacement for longer if and else conditional statements.

## Rewrite the following statement using a ternary statement

`(x===y) ? console.log(true) : console.log(false);`

## Things I want to know more about

I haven't got the chance to yet as I have spent way too much time on this assignment as is but it would be interesting to see how an answer given in a form can be saved without submitting the form and then compared with what is submitted by the user. From a data analytics perspective this can give a lot of insight to surveys.

## Sources To Cite

- [Forms](https://reactjs.org/docs/forms.html)

- [JavaScript — The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

- [Forms](https://react-bootstrap.github.io/forms/overview/)

- [Conditional Rendering](https://reactjs.org/docs/conditional-rendering.html)

- [Controlled vs. uncontrolled components in React](https://blog.logrocket.com/controlled-vs-uncontrolled-components-in-react/)
