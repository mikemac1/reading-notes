# Operators and Loops

## Operators

All complex expressions are joined by operators, such as `=` and `+`.

**Comparison Operators**: A comparison operator compares its operands and returns a logical value based on whether the comparison is true.

`Operator` - Description  
`==` - Equal. Returns true if the operands are equal.

`===` - Strict equal. Returns true if the operands are equal and of the same type.

`!=` - Not equal. Returns true if the operands are not equal.

`!==` - Strict equal. Returns true if the operands are of the same type but not equal, or are of different type.

`>` - Greater than. Returns true if the left operand is greater than the right operand.

`<` - Less than. Returns true if the left operand is less than the right operand.

`>=` - Greater than or eaqual to. Returns true if the left operand is greater than or equal to the right operand.

`<=` - Less than or equal to. Returns true if the left operand is less than or equal to the right operand.

**Assignment Operators**: provides the assignment operators to assign values to variables with less key strokes.

`Operator` - Description  
`=` - Assigns right operand value to the left operand.
    `x = f()`

`+=` - Sums up left and right operand values and assigns the result to the left operand.
    `x = x + f()`

`-=` - Subtract right operand value from the left operand value and assigns the result to the left operand.
    `x = x - f()`

`*=` - Multiply left and right operand values and assigns the result to the left operand.
    `x = x * f()`

`/=` - Divide left operand value by right operand value and assign the result to the left operand.
    `x = x / f()`

`%=` - Get the modulus of left operand divide by right operand and assign resulted modulus to the left operand.
    `x = x % f()`

`x **= f()` - The exponentiation assignment operator raises the value of a variable to the power of the right operand.
    `x = x ** f()`

## Loops and Iteration

Loops offer a quick and easy way to do something repeatedly. There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. The various loop mechanisms offer different ways to determine the start and end points of the loop. There are various situations that are more easily served by one type of loop over the others.

**`for` statement**: A `for` loop repeats until a specified condition evaluates to false. When a `for` loop executes, the following occurs:
![for loop example](https://cdn.programiz.com/sites/tutorial2program/files/javascript-for-loop.png)

1. The initializing expression *initialExpression*, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
2. The `conditionExpression` expression or test condition is evaluated. If the value of `conditionExpression` is true, the loop statements execute. Otherwise, the for loop terminates. (If the conditionExpression expression is omitted entirely, the condition is assumed to be true.)
3. The `statement` executes in the for loop body. To execute multiple statements, use a block statement ({ }) to group those statements.
4. If present, the update expression `incrementExpression` is executed.
5. Control returns to Step 2.

**`while` statement**: A `while` statement executes its statements as long as a specified condition evaluates to true. A `while` statement looks as follows:
![while loop example](https://cdn.programiz.com/sites/tutorial2program/files/javascript-while-loop.png)

1. The condition test occurs before `statement` in the loop is executed.
2. If the condition returns `true`, `statemen`t is executed and the `condition` is tested again.
3. If the `condition` returns `false`, execution stops, and control is passed to the statement following `while`.

### References

- [Assignment operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#assignment_operators)
- [Comparison operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#comparison_operators)
- [for statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#for_statement)
- [while statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#while_statement)
- [while loop](https://www.programiz.com/javascript/while-loop)

### Return

[Home Page](/code-102/README.md)
