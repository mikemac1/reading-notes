# Reading Assignment 04

## Why This Matters

The hyperlinks was something I have seen before and can see how it can be utilized very easy. The CSS normal flow and positioning I can kind of see how it is implemented but really do not understand. The function calls and understanding declaration vs invoking is fairly straight-forward and is key in knowning as building JS functions will be our "bread and butter" skill set.

## Questions To Answer

### To Create A Basic Link, We Wrap Text Or Other Content Inside What Element

The text is wrapped just like `<a>`content`</a>`

### The `href` Attribute Contains What Information

`href` is the attribute that is required to link to the source which in most cases is to a URL or to a section of a page with fragment URL. Telephone numbers and email addresses can also be utilized for `href`.

### What Are Some Ways We Can Ensure Links On Our Pages Are Accessible To All Readers

A big part of accessibility is to have strong link text within the anchor element. The reader should not have to guess where the link goes. Another accessibility feature should have anchor links should go to valid URLs. Having a bogus link confuses screen readers and the appropriate semantic element should be utilized. Finally if a link opens a new window or opens a non-URL it should clearly state in the text what it is. `Alt` text should describe the expected behavior and what it goes to.  

### What Is Meant By “Normal Flow”

> In the normal flow, text elements are laid out from top to bottom, and from left to right in left-to-right reading languages (or from right to left in right-to-left reading languages). This is the default behavior of the web browser.
>
 >In the normal flow, block-level elements stack on top of one another and inline elements fill the available space. When the browsing window is resized, the block elements expand or contract to the new width, and the inline content reflows to fit. Objects in the normal flow influence the position of the surrounding content (sibling elements).
>
 > [Web Design in a Nutshell, 3rd Edition by Jennifer Robbins](https://www.oreilly.com/library/view/web-design-in/0596009879/ch21s01.html)

### What Are A Few Differences Between `block-level` And `inline` Elements

`Block-level` will fill all of the available inline space while `inline` will only take up the horizontal space it requires. `Block-level` items can have the width & height set by the developer while `inline` elements cannot have the width and height changed by default. The display: property needs to be set to the block or inline-block value in order to change the width or height.

### ___ Positioning Is The Default For Every HTML Element

**Static** positioning is the default for every HTML element.

### Name A Few Advantages To Using Absolute Positioning On An Element

Since absolute positioning takes normal flow out of context it puts the element in its own layer without being affected by any other element. This allows having seperate features without getting interfered by another element. Best use is for popups.

Absolute positioning provides the ability to stack items. So when a warning or critical notice is needed on a page for some specific step or when some step may have been missed an item can be immediately brought to light.

### What Is A Key Difference Between Fixed Positioning And Absolute Positioning

The difference is how its reference position is located. For absolute positioning the reference position is based on the item's parent position. For fix positioning, the item's position is based on the viewport and not any specific other element or item.

### Describe The Difference Between A Function Declaration And A Function Invocation

Declaring a function is defining what it will do such as converting celsius to fahrenheit. A function invocation is when the function is called up on to do something with specific parameters or by itself.

### What Is The Difference Between A Parameter And An Argument

A parameter is the values provided when a function is called to used those values to perform its calculation or steps. An argument is what is used that sits in place of the parameter to be called within the function.

### Pick 2 Benefits To Pair Programming And Reflect On How These Benefits Could Help You On Your Coding Journey

**Learning from fellow students** Diversity is about seeing a problem from everyone's viewpoint. Everyone comes from a different perspective that we may not see and may solve a problem with fewer steps or an approach that may work for multiple problems. When people are accepting of others the value added when two are together makes the benefits almost immediaet.

**Job interview readiness** This gives the immediate impact for myself and my colleagues that can make the difference in getting hired or not. Practicing and getting someone elses input as well as seeing how they approach a challenge and watching their strategy. Getting multiple looks at challenges and making changes can increase our job interview readiness and therefore make us more job ready.

## Things I Want To Know More About

- The normal flow & positioning reads on MDN web docs were difficult to read and after going thru a couple of times I still wasn't sure. Went to a different site and was able to get a better handle on flow. Positioning I'm still unsure.

- The content is getting harder and I can see the idea of stacked learning starting to occur but do not have nearly a strong handle on this like I did with the earlier reading assignments. My fear is if this is hard now, what is this going to be like in a couple of weeks.

## Sources Utilized

[Creating hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

[Normal Flow](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)

[Web Design in a Nutshell, 3rd Edition by Jennifer Robbins](https://www.oreilly.com/library/view/web-design-in/0596009879/ch21s01.html)

[Positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)

[Functions — reusable blocks of code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions)

[6 Reasons for Pair Programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)
