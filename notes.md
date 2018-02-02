- A class or id should have values that refers to the content of the element, not the appearance.

- HTML comments start with `<!--` and end with `-->`. CSS comments start with `/*` and end with `*/`.

- bold text with `<strong>` is to show semantic importance; strong importance. `<b>`, on the other hand, is to stylistically offset text (make it stand out from its context); keywords. italics with `<em>` is for stress emphasis. `<i>` is to convey text in an alternative voice like it were placed in quotation marks; foreign words.

- Heading should be used for semantics, not to make text bold or big.

- Text level vs Structural level elements

- `<div>`s provide no semantic value. HTML5 introduced new structurally based elements.

- Font stacks! A list of font families in order of preference. There are some nice examples online to get inspiration from.

### Semantic code
- HTML is the markup. CSS is the style.
- HTML is descriptive. CSS is all about appearances.

### Forms

On the client side, an HTML form is nothing more than a convenient user-friendly way to configure an HTTP request to send data to a server. This enables the user to provide information to be delivered in the HTTP request.

### Sending data

The body of a get request is usually empty. Because the body is empty, the data sent to the server using a form is appended to the url.

The body of a POST request is never displayed to the user, but is possible to access it with a browser developer tool.

## name vs id

- Typically, both the name and id attribute values are identical.
- The for attr in a label tag refferences an id.
- The name attribute applies mostly to input controls in forms, since the server gets a name/value pair when the form is submitted;
- Omitting the name attribute means the value will not be sent to the server, so be sure to remember to add it.
- names in a group of radio buttons are the same

## labels

-If the design must have a placeholder attribute acting like a label, be sure to include the label element and hide it with CSS. The lack of a label element prevents screen readers from being able to tell their user what the field is expecting, making it impossible for forms to be properly completed when using such a browser.

- Adding inputs inside our label elements is a convenient way of making the text for the label activate the corresponding input without having to add a for attribute on the label.

## Select and option elements

- If the content between the option tags is what we want to send when the form gets submitted, we don't need to add value attributes to the option element.


## Don't use tables for layout purposes

https://launchschool.com/lessons/2d134e42/assignments/327b6fe4

- Tables are costly. Sometimes you may need a tabular display to arrange non-tabular items; use a list or other semantic markup instead.

## Things to explore

- Screen reading software: examples of when proper semantics makes a difference

- HTML5: does it offer more grouping elements to replace divs with something more meaningful? Ex: figure tag

- What do you mean by "this element has a default ... property value"? Is it something that each browser/device applies to the element by default? Is it just because browsers follow a convention? Or is it a rule that is passed to the client?"

### Images

- alt attribute of a img tag: not only used by assisted technologies, but search engines. Helps convey the purpose of an image.

- jpg: faster load times or high color counts, photographs
- png: great for transparencies or low color counts, icons or backgrounds patterns

- setting both a height and a width to a image could break its aspect ratio

### Blog post

- Google used the time element to display a posting date in its search results.

### Lengths

- We omit units when using zero lengths because 0 is the same in any measurement.

### Layout with CSS: Box Model, Positioning and Floats Rules

- display: inline, inline-block, block
- float: left, right
- clear: left, right and both
- overflow: visible, hidden, scroll, auto
- position: static, absolute, relative, fixed

- block or inline formating context

- You can set overflow on a container to have it take up the remaining space within a row of floated elements. This is useful if your last element can take up the leftover space in a variable width layout.

- Setting display to none will render the page as though the element does not exist. visibility: hidden; will hide the element, but the element will still take up the space it would if it was fully visible.

- If the floated element is bigger than it's parent container, you may have to set the overflow property (auto or hidden).

### Entities

An HTML entity is a piece of text ("string") that begins with an ampersand (&) and ends with a semicolon (;) . Entities are frequently used to display reserved characters (which would otherwise be interpreted as HTML code), and invisible characters (like non-breaking spaces). You can also use them in place of other characters that are difficult to type with a standard keyboard.

Some special characters are reserved for use in HTML, meaning that your browser will parse them as HTML code. For example, if you use the less-than (<) sign, the browser interprets any text that follows as a tag.

To display these characters as text, replace them with their corresponding character entities, as shown in the following table.


### CSS Resets

- Choose one that you prefer and customize it to your needs;

### On figures (again?)

If an image is related to the text content, make that a figure element (even if the image doesn't contain any captions)
