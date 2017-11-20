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
- names in a group of radio buttons are the same

## Don't use tables for layout purposes

https://launchschool.com/lessons/2d134e42/assignments/327b6fe4

- Tables are costly. Sometimes you may need a tabular display to arrange non-tabular items; use a list or other semantic markup instead.

## Things to explore

- Screen reading software: examples of when proper semantics makes a difference

- HTML5: does it offer more grouping elements to replace divs with something more meaningful? Ex: figure tag

### Images

- alt attribute of a img tag: not only used by assisted technologies, but search engines. Helps convey the purpose of an image.

- jpg: faster load times or high color counts, photographs
- png: great for transparencies or low color counts, icons or backgrounds patterns

- setting both a height and a width to a image could break its aspect ratio



