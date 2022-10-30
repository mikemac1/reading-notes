# Reading Assignment 05

## Why This Matters

The CSS coverage for this reading was excellent and showed some strong fundamentals that can be applied. I need to take the time to practice these as well as find some tools that exercise these criteria.

## Questions To Answer

### What Is A Real World Use Case For The `alt` Attribute Being Used In A Website

Having a visually impaired user working with a screeen reader which automatically reads the content will also read the `alt` text to give the user an understanding of what the image is.

### How Can You Improve Accessibility Of Images In An HTML Document

The key is to deliver a usable experience for all users which include those impaired visually. The `alt` text attribute for `img` elements is the key in improving accessibility. When an image provides critical information to the user, the same information must be condensed but included in the `alt` attribute for the screen reader to read. Also, those users which have poor bandwidth and turn off downloading images in the browser rely on the same `alt` text to provide context the images was supposed to provide.

### Provide An Example Of When The `Figure` Element Would Be Useful In An HTML Document

The `figure` element provides a semantic container for images, and to clearly link the image to the caption. However, it isn't just images this can be utilized for. A `figure` could wrap several images, a small section of code, a video, or even audio.

### Describe The Difference Between A gif Image And An svg Image, Pretend You Are Explaining To An Elder In Your Community

An easy way to think of the difference between a gif and an svg is using the analogy of the progression of a car.  In the mid-20th century cars could easily get you from point A to B but not all the creature comforts of today didn't exist. So cars back then required windows needing to be rolled up and no air conditioning.  While cars today can "roll up" the window with a push of a button and can drive themselves practically.

The svg image is like a mid-20th century car and provides a way to create shapes, lines, apply colors, and low-quality diagrams by providing coordinates for the computer to draw.  The gif image is the car of today and provides high quality animated images.

### What Image Type Would You Use To Display A Screenshot On Your Website And Why

I would use a PNG format to display a screenshot because it is high quality with little image loss and can be viewed on all browsers.  Even though WebP is better quality no image loss, many basic image editors don't have the ability to create or use the format.

### Describe The Difference Between Foreground And Background Colors Of An HTML Element, Pretend You Are Talking To Someone With No Technical Knowledge

When thinking of the difference between the foreground color and background color, a good analogy is using a great picture of a family. The family is the focus of the picture to see everyone's smiling faces which is the foreground, while the area behind the family is considered the background and not as much focus is placed however the color of the background can enhance the focus on the family.

### Your Friend Asks You To Give His Colorless Blog Website A Touch Up. How Would You Use Color To Give His Blog Some Character

The Adobe color wheel has some interesting features that allows a developer to select multiple colors that are complimentary to each other. Using a set color selection allows multiple elements such as text, background, shadow, border, and other elements to look like they should go together.

### What Should You Consider When Choosing Fonts For An HTML Document

The one most significant factor when choosing a font is availability. The machine viewing the page must have the font available for it to view as the developer created. If utilizing an API where the fonts are available from a remote server this can be a problem without connectivity. Also if the stylesheet does not specify a font the machine carries as a default the text will not appear as designed. This is why when fonts are specified, secondary and tertiary choices are made to ensure a font the machine might have access to is utilized. Another factor is looking at multiple fonts for design that show some separation between sections or a header and its `<p>` text. A great site that I have tried is Google's Font comparison tool. I have listed it below in sources utilized.

### What Do Font-Size, Font-Weight, And Font-Style Do To HTML Text Elements

- **Font-size**: utilizes a value that will increase or decrease the size of lettering. Default size is 16px and values can be passed in px, em, & rem.

- **Font-weight**: is the appearance of the letters in terms of bold, light, extrabold, and normal.

- **Font-style**: have several different selection that include whether lettering capitalized, have different letters or numbers increase in size as compared to the actual font size, and font spacing between each other.

### Describe Two Ways You Could Add Spacing Around The Characters Displayed In An `h1` Element

One is the use of `letter-spacing` or `word-spacing` which can be maninpulated using number of px and the other is using `font-kerning` which has an auto, normal, and none values.

## Things I Want To Know More About

I need to look at finding a source on strategies of how certain colors go together between fonts, borders, and backgrounds to give a sharp & modern look.

## Sources Utilized

[Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

[Image file type and format guide](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types)

[Applying color to HTML elements using CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color)

[Fundamental text and font styling](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)

[Pairing typefaces](https://fonts.google.com/knowledge/choosing_type/pairing_typefaces)
