# Question 01. What is CSS and what is it used for?

# Answer:

1.CSS (Cascading Style Sheets) is a language that defines the presentation (style) of a web page, including layout, colors, fonts, and spacing. By separating style from content (HTML), CSS promotes maintainability and reusability of styles across different web pages.


# Question 02. Explain the concept of the CSS Box Model.

Answer: 

The CSS Box Model defines the rectangular box that surrounds every HTML element. It consists of four parts:

Content: The actual content of the element (text, images, etc.).

Padding: The space around the content but inside the border.

Border: The optional border surrounding the padding.

Margin: The space around the border outside the element.


# Question 03. How do you specify different styles for different elements (selectors)?

# Answer: 

CSS offers various selectors to target elements:

Element selector: Selects elements by name (eg, h1, p).

Class selector: Selects elements with a specific class (eg, .error, .highlight).

ID selector: Selects a unique element with a specific ID (eg, #main-content).

Descendant selector: Selects child elements of a specific parent (eg, div p).

Universal selector ( *): Selects all elements (use cautiously).



# Question 04. How do you achieve responsive design using CSS?

# Answer: 

Responsive design ensures a website's optimal viewing experience across various screen sizes (desktop, mobile, tablet). You can achieve this using:

Media queries: Target specific CSS styles based on the device's screen size, orientation, and resolution.

Fluid layouts: Use percentages for widths and heights instead of fixed pixels to adapt to different screen sizes.

Flexible images: Use the max-width: 100%;property to allow images to scale proportionally.



# Question 05. Explain the difference between inheritand initialkeywords in CSS.

# Answer:

inherit: An element inherits the property value from its parent element.

initial: Sets the property to its default value as defined by the browser.



# Question 06. How do you clear floats in CSS?

# Answer: 

Floats can sometimes cause layout issues. You can clear floats using the clearproperty on the following element:

clear: left;- Clear floats on the left side.

clear: right;- Clear floats on the right side.

clear: both;- Clears floats on both sides.



# Question 07. Describe the difference between display: blockand display: inline.

# Answer:

display: block- Makes the element behave as a block-level element, starting on a new line and occupying the full available width.

display: inline- Makes the element behave as an inline element, displayed on the same line as other inline elements (text, images) and only occupying its necessary width.



# Question 08. How do you position elements using CSS?

# Answer: 

CSS offers various positioning properties to control element placement:

static(default): Element is positioned according to the normal document flow.

relative: Element remains in its normal position, but you can offset its position relatively.

absolute: Element is removed from the normal document flow and positioned according to its containing element or the viewport.

fixed: Element is positioned relative to the browser window (fixed position on scrolling).
