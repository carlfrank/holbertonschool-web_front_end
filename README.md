Advanced HTML

Which guidelines to follow for HTML:

Use a DOCTYPE declaration to ensure proper rendering and compatibility with web browsers
Employ semantic HTML to improve SEO and accessibility.
Keep the code clean and well organized with proper indentation and comments.
Ensure the HTML is valid according to W3C standards to avoid errors and cross-browser compatibility issues.
Use quotes around attribute values and close all tags.
Include language attributes in the <html> tag to declare the language of the page.
How to create the skeleton of an HTML5 page:

The skeleton of an HTML5 page includes:

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Title</title>
</head>
<body>
    <!-- Page content goes here -->
</body>
</html>

How to use semantic HTML tags to structure a web page:

Semantic HTML tags provide meaning to the web page. Examples include <header>, <footer>, <article>, <section>, <nav>, and <aside>. Use them to define the structure and outline of your content.

Which use cases to use div vs span:

Use <div> for block-level elements, which typically start on a new line and take up the full width available.
Use <span> for inline elements, which do not start on a new line and only take up as much width as necessary.
The semantic value of header, main, footer, article, nav, section, aside:

<header>: Represents introductory content or a group of navigational aids.
<main>: Signifies the main content of the document, unique to that document.
<footer>: Contains information about the container it's within, usually authorship, related documents, and copyright information.
<article>: Represents a self-contained composition in a document, page, or site, that is intended to be independently distributable or reusable.
<nav>: Represents a section of a page that links to other pages or to parts within the page: a section with navigational links.
<section>: Represents a standalone section that doesn't have a more specific semantic element to represent it.
<aside>: Represents a portion of a document whose content is only indirectly related to the document's main content.
How to use headings (and why it’s important to follow the hierarchical order):

Headings <h1> to <h6> represent six levels of section headings. <h1> is the highest section level and <h6> the lowest.
Maintaining the order is important for accessibility, as screen readers use them to navigate content, and for SEO, as search engines use them to understand content structure.
How to make lists in HTML:

Ordered lists <ol> for lists where the order of the items matters.
Unordered lists <ul> for lists where the order does not matter.
List items <li> are used within either type of list to define each item.
The differences between media (SVG, GIF, PNG, JPG):

SVG: Scalable Vector Graphics, a vector image format that scales without losing quality, ideal for logos and icons.
GIF: Supports animation and transparency, limited to 256 colors, best for simple animations.
PNG: Supports millions of colors and transparency, best for complex images requiring transparency.
JPG: Supports millions of colors but no transparency, best for photographs.
How to structure data in a table:

<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
    <tr>
        <td>Data 3</td>
        <td>Data 4</td>
    </tr>
</table>

How to integrate a video into a web page:

Use the <video> tag with the src attribute pointing to your video file.
<video controls>
  <source src="movie.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

How to integrate an audio file into a web page:

Use the <audio> tag:

<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>

How to embed external content:

Use the <iframe> tag to embed external content like a webpage or a YouTube video.
<iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" title
