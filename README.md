# HTML-CSS8_2Grid-Template

HTML=
<!DOCTYPE html>: Declares the document type and version of HTML being used.
<html lang="en">: Defines the root HTML element and specifies the document's language as English.
<head>: Contains meta-information about the HTML document, like character encoding and page title.
<meta charset="UTF-8">: Specifies the character encoding as UTF-8 for proper text rendering.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport configuration for responsive web design.
<title>FEM grid</title>: Sets the title of the web page to "FEM grid."
<link rel="stylesheet" href="styles.css">: Links an external CSS stylesheet to style the HTML content.
<body>: Contains the main content of the web page.
<main>: Represents the main content of the page and is typically used to structure the primary content.
<section>: Divides the content into distinct sections or blocks.
<div class="flexo">: Defines a division or container with the class "flexo" for styling or layout purposes.
<img src="...">: Embeds an image in the page, with the "src" attribute specifying the image file URL and "alt" providing alternative text.
<h2>: Represents a level 2 heading for text with semantic importance.
<p>: Defines a paragraph of text.

CSS-
*: Selects all elements on the page.

box-sizing: border-box;: Sets the box-sizing property to ensure padding and borders are included in the element's total width and height.
margin: 0;: Removes default margins around elements.
padding: 0;: Removes default padding inside elements.
body: Selects the <body> element.

display: grid;: Specifies that the body should be a CSS grid container.
grid-template-columns: 10% 80% 10%;: Defines the columns in the grid with relative widths.
grid-template-rows: 1.5fr 7fr 1.5fr;: Defines the rows in the grid with relative heights.
max-height: 100vh;: Sets the maximum height of the body to 100% of the viewport height.
background-color: rgb(233, 233, 233);: Sets the background color of the body.
justify-content: center;: Centers the content horizontally within the grid.
main: Selects the <main> element.

grid-area: 2/2/3/3;: Specifies its grid area within the body grid.
display: grid;: Defines it as a CSS grid container.
grid-template-columns: repeat(4,1fr);: Sets the number and width of columns in the grid.
grid-template-rows: repeat(2,1fr);: Sets the number and height of rows in the grid.
grid-gap: 20px;: Defines the gap between grid items.
.one, .two, .three, .four, .five: Selects elements with specific class names.

grid-area: Specifies the grid area for each section within the main grid.
background-color: Sets the background color for each section.
border-radius: Adds rounded corners to the sections.
background-image: Sets a background image for the first section.
background-repeat: Defines the background image repetition behavior.
background-position: Specifies the background image's position.
padding: Adds padding to the sections.
color: Sets the text color in the sections.
.flexo: Selects elements with the class "flexo."

display: flex;: Makes the elements flex containers.
gap: Defines the gap between flex items.
img: Selects all <img> elements.

width: Sets the width of the images.
border-radius: Rounds the corners of the images.
h2: Selects all <h2> elements.

font-weight: Sets the font weight for level 2 headings.
font-size: Sets the font size for level 2 headings.
.flexo p: Selects <p> elements within elements with the class "flexo."

font-weight: Sets the font weight for paragraphs.
font-size: Sets the font size for paragraphs.
opacity: Adjusts the opacity (transparency) of paragraphs.
section .paraone, section .paratwo: Selects specific paragraphs within <section> elements.

font-weight: Sets the font weight for specific paragraphs.
font-size: Sets the font size for specific paragraphs.
margin-block: Sets the margin on the top and bottom of paragraphs.
opacity: Adjusts the opacity (transparency) of specific paragraphs.
