# CSS Selectors

# CSS Selectors

CSS selectors are patterns used to select the HTML elements that you want to style. With CSS selectors, you can apply styles to specific elements on your web page.

There are several types of CSS selectors, including:

- **Type selectors** - select elements based on their HTML tag name.
- **Class selectors** - select elements based on their class attribute.
- **ID selectors** - select elements based on their ID attribute.
- **Attribute selectors** - select elements based on their attribute name and value.
- **Pseudo selectors** - select elements based on their state or position.

CSS selectors are very powerful and allow you to create complex styles for your web page. By combining different types of selectors, you can target specific elements and apply unique styles to them.

## Type Selectors

Type selectors are the most basic type of selector in CSS. They select all elements of a given type and apply styles to them. For example, to style all `<h1>` elements on your web page, you would use the following CSS:

```
h1 {
  font-size: 36px;
  color: #333;
}

```

This will set the font size to 36 pixels and the color to dark gray for all `<h1>` elements on your web page.

## Class Selectors

Class selectors allow you to target elements based on their class attribute. To create a class selector, you need to add a period before the class name. For example, to style all elements with the class "button", you would use the following CSS:

```
.button {
  background-color: blue;
  color: white;
  padding: 10px;
}

```

This will set the background color to blue, the text color to white, and add 10 pixels of padding to all elements with the class "button".

## ID Selectors

ID selectors are similar to class selectors, but they target elements based on their ID attribute. To create an ID selector, you need to add a pound sign before the ID name. For example, to style the element with the ID "header", you would use the following CSS:

```
#header {
  background-color: gray;
  height: 100px;
}

```

This will set the background color to gray and the height to 100 pixels for the element with the ID "header".

## Attribute Selectors

Attribute selectors allow you to target elements based on their attribute name and value. For example, to style all elements with a "target" attribute, you would use the following CSS:

```
[target] {
  text-decoration: underline;
}

```

This will add an underline to the text of all elements with a "target" attribute.

## Pseudo Selectors

Pseudo selectors are used to select elements based on their state or position. Some examples of pseudo selectors are:

- `:hover` - select an element when the mouse pointer is over it.
- `:active` - select an element when it is being clicked.
- `:first-child` - select the first child element of a parent element.
- `:last-child` - select the last child element of a parent element.

For example, to change the color of a link when the mouse pointer is over it, you would use the following CSS:

```
a:hover {
  color: red;
}

```

This will change the color of all links to red when the mouse pointer is over them.

In conclusion, CSS selectors are an essential part of web development that allow you to target specific elements and apply styles to them. By mastering CSS selectors, including pseudo selectors, you can create beautiful and responsive web pages that look great on any device.
