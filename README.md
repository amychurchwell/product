# _Product Showcase_

#### _A web application, November 17, 2017_

#### By Amy Churchwell

## Description

A single-page site that showcases a product for sale. In this case, donuts.

## ELEMENTS USED

| TERM  | DESCRIPTION  | IMPLEMENTATION |
|---|---|---|
| BOX-SIZING  | This property tells the browser what parts of the box model should be included in the elements total width and height.  | In this project, I used box-sizing: border-box to move margin and padding inside content so the set width would not be changed.|
| FLOAT  | This property takes and element out of the normal flow of its containing element, without removing it from the flow entirely. The values specify the direction the element should be moved.  | I used float to determine the position of elements inside their containers. |
|   DISPLAY: BLOCK   | The element generates a block element box.  | display:block was used on the logo typeface because I wanted to treat it like an image in terms of positioning.  |
|   DISPLAY: INLINE   | The element generates one or more inline element boxes.  | display: inline was on the gallery images to display them in a row.  |
|   CENTERED CONTENT   | Horizontally centering a block element.  | To center content in this project I often set a defined width on an element and then used margin: auto to divide the margins equally. |
|   PSEUDO-ELEMENT   | A keyword added to a selector that lets you style a specific part of the selected element(s).  | I used box-sizing: border-box on everything on the page. For simplicity's sake, I used: *, *::before, *::after |
|   PSEUDO-CLASS   | A special state of an element.  | One example of a use of pseudo-class on this page is the :hover state on gallery images and links.  |
|   CLEAR-FIX   | Elements after a floating element will flow around it.  | In this situation, clear-fix was not needed. I used overflow: hidden for the image gallery because I wanted a uniform size. |
|   POSITIONAL SELECTOR   | A pseudo-class that matches one or more elements based on their position among a group of siblings.  | I used positional selectors a lot when styling the nutrition table. For example, I wanted every second table data in a row to align right instead of left: *:nth-child(2)* was used on td.  |
|   SELECTOR COMBINATOR   | A combinator is something that explains the relationship between the selections.  | Selector combinators were used regularly in situations that required more specificity. For example, li a:hover = only list item links in the hover state. |

## Setup/Installation Requirements

#### GITHUB PAGES
* Open web browser and go to the [GitHub Pages][4].

[4]: https://amychurchwell.github.io/product/ "GitHub Pages"

## Known Bugs

No known bugs.

## Support and contact details

_Please do not hesitate to contact me at amy.churchwell@gmail.com with any feedback or questions._

## Technologies Used

* _CSS_
* _Normalize.CSS by Nicolas Gallagher_

### License

Copyright (c) 2017 **_Amy Churchwell, Student at Epicodus._**
