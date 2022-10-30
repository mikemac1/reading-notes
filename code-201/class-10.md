# Reading Assignment 10

## Why This Matters

Understanding how a developer writes code is important. However not all developers are reliant upon just themselves to debug code. Many developers must test/debug other developers's code and using a JS debugging tool gives any tester a great starting point to narrow down where a problem may exist.

## Questions To Answer

### Name some key differences between a Syntax Error and a Logic Error

Syntax errors is when the computer cannot understand the code the developer has written. Those errors can be something as simple as a spelling error with a function, variable or method called. The error can get a little more complex like assigning a variable a null value which should have been assigned a different data type or when a a curly bracket, paranthesis, comma, or semicolon has been forgotten, mistyped or in the wrong spot. What makes all of this bearable is the console window will give an indication of the syntax issue and may even point exactly where the issue is with identifying the line location number.
Logic errors can be much harder to identify. These are errors where the syntax is actually correct but the code the developer wrote is not what the original intention was.  Maybe it is a math function where in istead of multiplying, the function divided, added or subtracted. A logic error could be when something was supposed to print out on the screen but only a portion of a message displayed or even nothing at all. What makes logic error more challenging than syntax errors is the console log provides no indication of where the logic error is. Only what the developer programmed it to do. This is why `console.log()` messages in the middle of functions or in strategic places gives an indication of when program logic is functioning as intended.

### List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them

I have encountered a ton of logic and syntax errors. Most have been corrected with the help of a T/A but some I've been able to resolve because of the console log whether they were syntax or logic errors.  It has taught me to utilize the console.log more effectively when I build a function where a majority of my trouble is. For instance building a nest for loop inside of another and not gaining access to the data in an array because of poor construction. The console log I could see what was getting returned versus what I wanted. The other piece that I think has done a tremendous job in minimizing errors for me versus fighting to overcome them when they pop up has been using pseudo code. This past week I've worked really hard in coming up with steps to where I want to get to in gaining an answer and the syntax error has been much less likely. The logic error is still happening but the syntax error is definitely less. One example of a logic error was get the first blank cell in the top header prior to calling down and places the hours across the header row. Doing the latter turned out to be easy, but my logic in producing the first cell blank was originally done every other hour because I included it in the loop.  Again I ended up seeing that with a `console.log` command.

### How will this topic continue to influence your long term goals?

I am definitely more aware of them with the use of console.log and pseudo code in minimizing the errors that come along. However I have to understand that errors are going to happen and they are a part of learning. Unfortunately being a perfectionist it is really tough to accepting that fact.  **REALLLLLY** tough. In the short term I do need to practice writing functions that are succinct. It has created a lot of rework recently where because I like to include a lot of steps to have a function produce everything it can be tough to follow and dissect later when changes need to be made. From a long term perspective I hope making these changes now will make me a better coder. I know it will take practice and continued implementation to using these methods as well as not alowing the errors to sandbag me into giving up.

### How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?

The JS debugger exists in most browsers today and provides a lot more power than what you will use with just `console.log()`. When testing or attempting to debug a set of code that may not be yours, the debugger allows the developer to check just sections or even a line of code to perform debugging and attempts to give some direction on what might be the problem. The `console.log()` method really only tells you if the section of code you are inspecting got to the `console.log()` but that doesn't tell you anything.

### Define what a breakpoint is

Use breakpoints to pause your JavaScript code at a specific point. For the browser Chrome it has several different types including:

- Line-of-code: on an exact region of code.
- Conditional line-of-code: on an exact region of code, but only when some other condition is true.
- DOM: on the code that changes or removes a specific DOM node, or its children.
- XHR: when an XHR URL contains a string pattern.
- Event listener: on the code that runs after an event, such as click, is fired.
- Exception: on the line of code that is throwing a caught or uncaught exception.
- Function: whenever a specific function is called.

## What is the call stack?

The **Call Stack** section shows the developer what code was executed to get to the current line. It may show the function that handles a calculation, an event handler, or DOM element addition where the code will be paused on the breakpoint.

## Sources Utilized

[What went wrong? Troubleshooting JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong)

[The JavaScript debugger](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools#the_javascript_debugger)

[Debugging HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Debugging_HTML)

[Debugging CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Debugging_CSS)

[Pause your code with breakpoints](https://developer.chrome.com/docs/devtools/javascript/breakpoints/)
