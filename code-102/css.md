# Cascading Style Sheets

## What is CSS?

CSS (Cascading Style Sheets) allows coders to create great-looking web pages. Starting with very basic document text styling, like changing the color and size of headings and links. It can also be used to create a layout for instance turning a single column of text into a layout with a main content area and a sidebar for related information. It also can even be used for effects such as animation.

## CSS Syntax

CSS is a rule-based language, The coder defines the rules by specifying groups of styles that should be applied to particular elements or groups of elements on the web page. An example below shows the syntax:
![CSS Syntax](https://www.w3schools.com/css/img_selector.gif)

- Selector: The selector points to the HTML element you want to style.
- Declaration: The declaration block contains one or more declarations separated by semicolons. Each declaration includes a CSS property name and a value, separated by a colon.
- Property: a property specifies what to style the targeted HTML element(s)
- Value: is what the property will do. For instance the first value is the font color will be blue.

## Selectors

A selector is simply the element to be styled. But selectors aren't just elements. They could be attributes, pseudo-classes, ids, classes, and descendants. Here are some examples of selectors:

- Universal: indiated by an asterisk. This selector affects every single element on the document tree.
- Element: the most common selector, and it involves targeting members of a particular element when that element is defined. Examples include p, h2, footer, etc.
- Classes & IDs: defined in the HTML and earmarked in the CSS using '.' (for classes) and '#' (for IDs). They target HTML elements with specific class or ID names.
- Pseudo-Classes: are classes that are based on their state. Their state is also a response to user actions. Pseudo-classes do not stand alone on their own. They are attached to other selectors, followed immediately by a colon, then state. Hover, visited, before and active are common pseudo-classes.

## How To Insert CSS

There are three ways of inserting a style sheet:

- External CSS: With an external style sheet, you can change the look of an entire website by changing just one file! Each HTML page must include a reference to the external style sheet file inside the *link* element, inside the head section.
- Internal CSS: An internal style sheet may be used if one single HTML page has a unique style. The internal style is defined inside the *style* element, inside the head section.
- Inline CSS: An inline style may be used to apply a unique style for a single element. To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

References:

- [What is CSS?](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)
- [CSS reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
- [How To Add CSS](https://www.w3schools.com/css/css_howto.asp)
- [CSS Selector Reference](https://www.w3schools.com/cssref/css_selectors.asp)

### Return

[Home Page](/code-102/README.md)
