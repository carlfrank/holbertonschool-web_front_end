Selectors, Properties, and Values:

Selectors are patterns used to select the elements you want to style. For example, h1 will select all <h1> elements.
Properties are the ways in which you can style an element. For example, color is a property that defines the text color.
Values are assigned to properties to specify how to style the elements. For example, #FF0000 is a value that could be used with the color property: color: #FF0000;.
The Difference Between Block and Inline Styling:

Block elements like <div>, <p>, and <h1> take up the full width available, stacking vertically.
Inline elements like <span>, <a>, and <img> take up only as much width as needed and do not break the line.
How to Ensure Consistency Across All Browsers (CSS Reset):

A CSS Reset is a set of CSS rules that removes all built-in browser styling. For instance, margins, paddings, font sizes, and so on are set to a consistent baseline so that you can build your styling on a consistent canvas across different browsers.
How to Set Up CSS Variables:

CSS Variables are entities defined by CSS authors that contain specific values to be reused throughout a document. They are set using the -- prefix and accessed using the var() function. For example:

:root {
  --main-bg-color: #ff0000;
}
body {
  background-color: var(--main-bg-color);
}

The Differences Between Inline, Embedded, and External CSS:

Inline CSS is placed directly within the HTML tags using the style attribute.
Embedded CSS is placed within the <style> tag in the HTML document's <head> section.
External CSS is placed in a separate file and linked to the HTML document with a <link> tag.
How Grid Systems Work (with Floats):

Grid systems based on floats are a way to create complex layouts by floating elements to be left or right within a containing element, usually a row, and giving them percentage-based widths.
The Difference Between Icon Webfonts and SVG Icons:

Icon Webfonts are fonts that contain symbols and glyphs instead of traditional letters. They are scalable like text and can be styled with CSS.
SVG Icons are images based on XML and can be scaled without loss of quality. They often have smaller file sizes and can be manipulated through CSS and JavaScript.
The Difference Between Pseudo-classes and Pseudo-elements:

Pseudo-classes are used to define the special state of an element. For example, :hover changes the style when the user hovers over an element.
Pseudo-elements are used to style specified parts of an element. For example, ::before creates a pseudo-element that is the first child of the selected element.
How to Make Background Gradients:

CSS gradients are created using the background-image property along with the linear-gradient() or radial-gradient() functions. For example:

background-image: linear-gradient(to right, red, yellow);

How to Animate Elements in CSS:

CSS animations are achieved using the @keyframes rule and the animation property. @keyframes are used to define the styles that the animation will have at certain times.
How to Transform (2D, 3D) Elements:

The transform property is used in CSS to apply 2D or 3D transformations to elements. 2D transforms include rotate(), translate(), scale(), etc., and 3D transforms include rotateX(), rotateY(), translateZ(), perspective(), etc.
What Vendor Prefixes Are:

Vendor prefixes are used to add support for new CSS features before they are fully supported in all browsers. Prefixes like -webkit- (for Chrome, Safari), -moz- (for Firefox), -o- (for Opera), and -ms- (for Internet Explorer) are used in front of the CSS property or value.