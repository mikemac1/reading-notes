# Programming with JavaScript

## Control Flow

The control flow is the order in which the computer executes statements in a script. Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops.

For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, ;eaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure like an *if...else* statement, so that different code executes depending on whether the form is complete or not.

A typical script in JS includes many control structures, including conditionals, loops and functions. Parts of a script may also be set to execute when events occur.

## JS Functions

A function is a block of code designed to perform a particular task and is executed when *something* invokes it (calls it).

### Function Syntax

A JS function is defined with the function keyword, followed by a name, followed by parentheses (). Function names can contain letters, digits, underscores, and dollar signs (same rules as variables). The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)
The code to be executed, by the function, is placed inside curly brackets: {}
![Function Example](https://www.tektutorialshub.com/wp-content/uploads/2021/06/Javascript-Functions.png)

Function parameters are listed inside the parentheses () in the function definition. Function arguments are the values received by the function when it is invoked. For the example above, width & height would be brought in. Inside the function, the arguments (the parameters) behave as local variables. Then JS reaches a return statement, the function will stop executing. Functions often compute a return value. The return value is "returned" back to the "caller"

## JS Operators

JS operators perform some operation on single or multiple operands (some data value) and produces a result. For example with in 1 + 2, the + sign is an operator and 1 is left side operand and 2 is the right side operand. The + operator performs the addition of two numeric values and returns a result.

### Types of JS Operators

**Arithmetic Operators**: used to perform mathematical operations between numeric operands.

`Operator` - Description  
`+` - Addition

`-` - Subtraction

`*` - Multiplication

`**` - Exponentiation

`/` - Division

`%` - Modulus (Division Remainder)

`++` - Increment

`--` - Decrement

**Comparison Operators**: comparison operators that compare two operands and return a boolean value true or false.

`Operator` - Description  
`==` - Compares the equality of two operands without considering type.

`===` - Compares equality of two operands with type.

`!=` - Compares inequality of two operands

`>` - Returns a boolean value true if the left-side value is greater than the right-side value; otherwise, returns false.

`<` - Returns a boolean value true if the left-side value is less than the right-side value; otherwise, returns false.

`>=` - Returns a boolean value true if the left-side value is greater than or equal to the right-side value; otherwise, returns false.

`<=` -Returns a boolean value true if the left-side value is less than or equal to the right-side value; otherwise, returns false.

**Assignment Operators**: provides the assignment operators to assign values to variables with less key strokes.

`Operator` - Description  
`=` - Assigns right operand value to the left operand.

`+=` - Sums up left and right operand values and assigns the result to the left operand.

`-=` - Subtract right operand value from the left operand value and assigns the result to the left operand.

`*=` - Multiply left and right operand values and assigns the result to the left operand.

`/=` - Divide left operand value by right operand value and assign the result to the left operand.

`%=` - Get the modulus of left operand divide by right operand and assign resulted modulus to the left operand.

**Logical Operators**: used to combine two or more conditions. JavaScript provides the following logical operators.

`Operator` - Description  
`&&` - known as **AND** operator. It checks whether two operands are non-zero or not (0, false, undefined, null or "" are considered as zero). It returns 1 if they are non-zero; otherwise, returns 0.

`||` - known as **OR** operator. It checks whether any one of the two operands is non-zero or not (0, false, undefined, null or `""` is considered as zero). It returns 1 if any one of of them is non-zero; otherwise, returns 0.

`!` - known as **NOT** operator. It reverses the boolean result of the operand (or condition). !false returns true, and !true returns false.

**Type Operators**:

`Operator` - Description  
`typeof` - Returns the type of a variable

`instanceof` - Returns true if an object is an instance of an object type

References:

- [Control Flow](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)
- [Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)
- [More Functions](https://www.w3schools.com/js/js_functions.asp)
- [JavaScript Operators](https://www.w3schools.com/js/js_operators.asp)
- [Expressions and operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

### Return

[Home Page](/code-102/README.md)
