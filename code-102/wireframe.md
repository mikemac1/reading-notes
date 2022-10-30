# Structured Web Pages with HTML and Wireframes

## Wireframe

A wireframe is low density design plan of what the architecture will look like. Wireframes are created for each different screeen of an app as an example.  There are two types but they are both made up of same basic fundamental shapes to represent the key elements of what a user would see on a screen in their simplest form. They are:

    - Hand drawn sketch: is simply using paper, pen or marker
    - Digital: a variety of different tools available both paid & free. These include balsamiq, margel or wireframe cc.

The important thing to note about wireframes is to keep it simple and answer some basic questions about the site. For example:

- Is it a mobile device or is it a desktop monitor?
- On the home page does the user login?
- Where might the logo of the company reside?
- Are there going to be links to the organization's social media sites?
- What statement(s) or picture(s) might we want to have?
- Where might the links to other pages on the site reside?

## HTML (HyperText Markup Language)

Put simply HTML manages the content on the web page by utilizing *elements* which "enclose" or wrap the content and causes it to act in a certain way. An element consists of four main parts:

- An Opening Tag:  This consists of the name of the element wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect.
- A Closing Tag:  This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.
- The Content: This is the whole reason for HTML and is usually just text but can be an image.
- Attributes (OPTIONAL): Contain extra information about the element but don't want it to appear with the content.

In the two images below, the parts of an element are displayed.
![Opening and closing tags with content](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics/grumpy-cat-small.png)

![Attribute part of an element](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics/grumpy-cat-attribute-small.png)

## Anatomy Of A Web Page

`!DOCTYPE html` — the required preamble which identifies the type of page the browser will see.
`html` — the *html* element wraps all the content on the entire page and is sometimes known as the root element.
`head` — the *head* element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations, and more.
`meta charset="utf-8"` — This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages.
meta name="viewport" content="width=device-width"> — This *viewport* element ensures the page renders at the width of viewport, preventing mobile browsers from rendering pages wider than the viewport and then shrinking them down.
`title` — the *title* element sets the title of your page, which is the title that appears in the browser tab the page is loaded in.
`body` — the *body* element contains all the content that you want to show to web users when they visit your page, whether that's text, images, videos, games, playable audio tracks, or whatever else.

## SEMANTICS

In programming, Semantics refers to the meaning of a piece of code — for example "what effect does running that line of JavaScript have?", or "what purpose or role does that HTML element have" (rather than "what does it look like?".)

For example, in HTML, the *h1* element is a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page."

However, a semantic element can be overridden by HTML, CSS or JS code. HTML should be coded to represent the data that will be populated and not based on its default presentation styling. Presentation (how it should look), is the sole responsibility of CSS.

Examples of semantic HTML code include:

- `article`
- `aside`
- `details`
- `figcaption`
- `figure`
- `footer`
- `header`
- `nav`
- `section`
- `time`

Keep in mind there are roughly 100 semantic elements.

References:

- [The Definitive Guide: How To Make Your First Wireframe](https://careerfoundry.com/en/blog/ux-design/how-to-create-your-first-wireframe/)
- [HTML basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)
- [Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)
- [HTML elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

### Return

[Home Page](/code-102/README.md)
