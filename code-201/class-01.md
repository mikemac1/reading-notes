# Reading Assignment 01

## Why This Matters

The reading assignment is really the basics of what happens behind the scenes between the user at their machine to the webpage they are trying to access that resides on the server. It also gives the foundation for the type of elements that make up a typical web page. Including how JavaScript (JS) fits in with the page and why it makes a difference in how users interact with a webpage.

## Questions To Answer

### An Acrostic HTML & Parsing Poem

**C**alling for a web page requires two parties

**O**ne is the client

**D**uring the time a request is being sent by the client a server awaits

**E**ach has their distinct role

**F**ollowing the request a response is served

**E**ach HTML response is parsed by the client's browser

**L**onely, the parser encounters a reference to a script file

**L**oopy, the parser stops parsing & requests the script file

**O**rdering the script from the server, the parser executes

**W**hile the client's browser finishes reading the HTML

**S**ampling the full response, a web page is born

    Written by Mike McCarty

### Describe How HTML, CSS, and JS Files Are “Parsed”

Parsing is a very critical step from having a webpage on a server to seeing the page on the user's screen. A client's browser must have the HTML data and links to external CSS & JS files. The intial step for parsing is building the page based on the DOM (Document Object Model) & utilizing tokens. The tokens can assign specific pieces that represent pieces of the DOM and to be requested from the server. It is important for developers to understand this process as it greatly impacts latency & how the client's machine is single threaded. Bottom line a user wants their page quickly and design of a webpage can impact how a browser parses the HTML, CSS, & JS data.

### How To Find Images To Add To A Website

The issue is never about finding an image that looks good. The issue for me as a developer is to ensure that an image is not copyrighted. The easiest way is to utilize Google's image search feature and in options use the "Creative Commons licenses" selection to ensure the image is available for usage.

![Example searching for creative commons](cclicense.jpg)

### "String" vs A Number

Visualizing a string versus a number in javascript is all about ' ' or " ". For example:

    - 24
    - "24"
      - The first 24 is the number, while "24" is the string.

### What Is A Variable And Why Are They Important In JS

A variable can be considered a proxy, to a permanent or temporary place that holds some value whether it be a string, number or an object. Having a variable makes JS powerful for a couple of reasons. One it gives the programmer an easy way to store a value by giving it a name that makes sense to those who are reading the code. Second, the fact that variables can temporarily store a value gives JS the ability to have a variable a part of a function that asks a user a question or has a graphic move on a website.

### What Is An HTML Attribute

An attribute provides an option(s) to add to additional functionality to an HTML element. One example of that functionality is to add a class or id to an HTML element to provide CSS style properties to the element on a page. Another example can be to provide dimensions to a picture in the `img` element overriding the inherent dimensions the picture already has.

### Describe the Anatomy of an HTMl element

THe construction of an HTML element is to surround content with elements to provide structure for the browser to display. It starts with an opening tag, whether it identifies as a type of heading, place on the page like a header or footer, or maybe it is a paragraph.  Each opening tag may contain some attribute, then the content is listed, and followed by the closing element's tag.  In some instances the opening tag may be self-closing. For example `img` or `br`.
![Example of an HTML element](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics/grumpy-cat-small.png)

**REFERENCE**: [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)

### What Is The Difference Between `article` And `section` Element Tags

The HTML article element can be utilized for a specific block of content such as a forum or blog post. The article is going to seperate the content on the page.
Coders will usually use the section element to divide long documents into chapters, or create different tabs, or divide various themes on the page.

### What Elements Does A “Typical” Website Include

HTML utilizes some common tags for typical areas in a website. They are:

- header: `header`
- navigation bar: `nav`
- main content: `main` with various content subsections including:
  - `article`, `section`, and `div` elements
- sidebar: `aside`
- footer: `footer`

### How Does Metadata Influence Search Engine Optimization

Metadata utilizes a content attribute that can contain a description about the site as well as keywords that users may search with. Meta tags are critical because search engines are impacted by what the meta tag displays as users' web inquiry has a similar keyword. As keywords within the meta tag get "hit" by web queries the search engine's results ranking will increase for that site.

### How Is The `meta` HTML Tag Used When Specifying Metadata

There are a few attributes that go with `meta` that assist in specifying metadata:

- `name`: this provides context for what is within the content attribute. Some of the more common values for name are application-name, author, description, generator, keywords, & viewport.
- `content`: this attribute will provide text the coder enters based on the value of the name attribute. For example a name value of author will generate the author's name for the page.
- `charset`: will specify the character set for the browser. In most cases `charset` will be set to UTF-8 encoding which is set by the Unicode standard. This standard is supported in many operating systems and clients' browsers.
- `viewport`: specifies what a user's visible area for a web page on a device. The attribute's values include width, height, initial-scale, minimum-scale, maximum-scale, and user-scalable.

### What Is The First Step To Designing A Website

Project ideation is the first step in designing a website. It requires asking some basic questions before even beginning the steps or designing or building the site. The questions to be answered are:

1. **What exactly do I want to accomplish?**
This question should provide answers to the audience trying to be attracted, the type of goods or services being advertised, the discussions trying to be conversed, or imagery the subject generates.

2. **How will a website help me reach my goals?**
This question should provide the answer of what makes this site addresses other web sites don't address or do a poor job in conveying.

3. **What needs to be done, and in what order, to reach my goals?**
Answering what needs to be accomplished must be prioritized. For instance the images that are going to populate the site are they owned by the site owner or do licensing rights have to purchased as a possible task. If goods are going to be purchased by site visitors supply chain management must be considered as a top priority. For all of these examples, practical steps must be identified & prioritized so one step is not waiting on previous steps and delaying the deployment of the site.

### What Is The Most Important Question To Answer When Designing A Website

What exactly the builder wants to accomplish is the most important question to be answered as it drives everything else.

### Why Should You Use An `h1` Element Over A `span` Element To Display A Top Level Heading

Utilizing an `h1` element delineates the text it wraps as the top level heading for the page. Using the `span` element means the content does not inherently represent anything and is a generic inline container for phrasing content. Not using the semantic elements for what they were designed for hinders follow on development as coders will have to interpret what the original developer was attempting to code.

### What Are The Benefits Of Using Semantic Tags In Our HTML

The following benefits are due to the use of semantic tags in HTML:

- semantic tags can assist screen readers for disabled users.
- with the use of semantic tags provides a coder an easier time of finding blocks of meaningful code.
- it tells the developer the type of data that will be populated

### Describe 2 Things That Require JS In The Browser

When a webpage utilizes an API (Application Programming Interface) JS is required to pull the code & data to populate the site. For instance Twitter & Google Maps utilized APIs and the webpage would not work without JS. Another requirement for JS is creating dynamic web pages which take action based on a user action such as mouse click that may generate a video or an audio file is played.

### How Can You Add JS To An HTML Document

There are three options to add JS.

- Internal JavaScript: is the usage of a `script` tag within the `head` element that contains all of the JS code for the page.
- External JavaScript: found in a single file which several webpages can reference. This provides code reusability and adds speed to maintaining.
- Inline JavaScript handlers: This is not recommended but the code is written inside a `script` element at a specific location on an HTML document. The reason it is not recommended is it makes it very difficult for developers to maintain as the project scale increases.

## Things I Want To Know More About

## Sources Utilized

[Article vs Section Elements](https://www.positioniseverything.net/html-article-vs-section)

[Getting Started With HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

[Document and website structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

[Meta Tages in SEO](https://www.searchenginewatch.com/2018/04/04/a-quick-and-easy-guide-to-meta-tags-in-seo/)

[Standard Meta Tags](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta/name)

[How do I start to design a website](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding)

[Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

[What is JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)
