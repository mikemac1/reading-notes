# Reading Assignment 11

## Why This Matters

Developers need to understand the different environments users are coming with when viewing the sites they create. Whether it is an Apple or Android phone, a laptop versus a desktop or Safari or Chrome or Edge. Having a site that is designed with responsiveness in mind means it can have a successful integration with many different environments.

## Questions To Answer

### Explain how the ability to use video and audio on the web has evolved since the early 2000s

Simply, video and audio formats were very limited with both the available types of files which had limited quality to the applications utilized to display, edit and play those media files. Besides the early security issues many of the plugins were specific to a browser (like Netscape or IE) and were not manufacturer agnostic. Today a viewer or editor can handle almost all file types and APIs are generic such that HTML, CSS & JS can be written to support all of them.

### Describe the use of the `src` and `controls` attributes in the `<video>` element

`controls`: are an attribute that will give the browser controls to allow the user to control video playback, including volume, seeking, and pause/resume playback.

`src`: is the location for the URL to embed. This is optional as the `<source>` element within the video block can specify the video to embed.

### Why is it important to have fallback content inside the `<video>` element?

It is possible that either the browsers trying to display the video are not compatible with the necessary plugin or the source of the video may not be available if pointing to a remote source.  If the browser doesn't support video playback or is unavailable, the fallback content can be text and/or images.

### Write a very short story where `<audio>` and `<video>` are characters

Audio and Video were the best of buddies. Their parents, both great sets of developers would often place them together in different playgrounds to practice their special talents. Unfortunately not all playgrounds were made the same so they found their talents may not be put to their best capabilities. For instance they could really do their "thing" when they went to Chrome, the best of all playgrounds. Both Audio & Video would play their talents with great quality in sight and sounds. However they couldn't stand Netscape.  Nothing would ever come out right! They often hoped Netscape would get torn down so they could have another Chrome to play on!

### How does Grid layout differ from Flex?

The basic difference between Grid and Flexbox is that flexbox was designed for a layout in one dimension using either a row or a column. Grid was designed for two-dimensional layout - rows, and columns at the same time.

### Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences

**Grid container**: like in flexbox, it is the direct parent of the items to be placed in grid. The constainer consists of grid items which are placed inside columns & rows.

**Grid item**: are the direct descendants of the grid container. Each column has one grid item per row.  However, the item can be styles so it spans multiple rows and/or columns.

**Grid line**: are the horizontal and vertical lines that make up the grid and surround the grid items falling within the container. The lines between columns are called column lines, while the lines between rows are called row lines. They are referred by line numbers when placing a grid item in a grid container.

### Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

For a couple of reasons first is bandwidth restrictions. If a user is limited to the amount of bandwidth they can consume, having an image which is bandwidth intensive does not help a user if another image is available that can take up a smaller amount of data and is similar in quality.  Second although a large screen between two users is the same size, one monitor may show greater details with an image than another monitor. That is why technologies were developed to allow a browser to make a selection across several image types in order to best display the one on the monitor.

### Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used

`srcset`: will sepecify a list of image files to use in different situations.
For example:
`<img src="img/puppyLaszlo.jpg" alt="A black lab puppy named Laszlo jumping for a ball." srcset="img/puppyLaszlo-highres.jpg 2x">`
The base image can be replaced by the browser to use the `srcset` to gain 2x the resolution.
`sizes`: will specify image sizes for different page layouts
<img src="img/puppyLaszlo.jpg" alt="Black lab puppy named Laszlo jumping for a ball." \
    srcset="
    puppyLaszlo-s.jpg  300w,
    puppyLaszlo-l.jpg  600w"
  sizes="(max-width: 500px) 300px,
         800px"
>
Max width is for a viewport's max width of 500px the width of image uses will be 300w while the 800px will use the 600w image.

### How is `srcset` more helpful for responsive images than CSS or JavaScript?

When the browser starts to load a page, it starts preloading any images before the main parser has started to load and interpret the page's CSS and JS. That mechanism is useful in general for reducing page load times, but it is not helpful for responsive images — which is why the attribute srcset would be the preferred method to decrease page loading time.

## Sources Utilized

[Video and audio content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

[A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

[Relationship of grid layout to other layout methods](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Relationship_of_Grid_Layout)

[Responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

[Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

[From object to iframe — other embedding technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)

[A Guide to the Responsive Images Syntax in HTML](https://css-tricks.com/a-guide-to-the-responsive-images-syntax-in-html/#using-srcset)

[CSS Grid Layout Module](https://www.w3schools.com/css/css_grid.asp)
