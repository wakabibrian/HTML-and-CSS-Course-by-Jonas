# HTML-and-CSS-Course-by-Jonas

## Types of Boxes:

**1. Inline Boxes**
These occupy only the spaces that they need. They don't create line breaks after them. e.g img, button, strong, em, a elements

- height and width do not have any effect
- Paddings and margins are only applied horizontally

- display: inline

**2. Block level Boxes/elements**
These occupy the space that they can and create line breaks after them. They can not be side by side with one another e.g p , h1-h6, body, main, ol, ul, footer, aside etc elements (most of them)

- display: block

**3. Inline-Block level Boxes/elements**
Look like inline elements on the outside but behave like block level elements on the inside
Do only occupy the space that they need for their content and they cause no line breaks
Box-model applies as showed. We can still set height and width, and we can still use margins and paddings
Images (img element) are inline-block level elements

- display: inline-block
