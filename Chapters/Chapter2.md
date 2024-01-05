
# Chapter 2: Selectors and Properties

In this chapter, we'll dive deeper into the world of CSS by exploring selectors and properties. These are fundamental concepts that allow you to target specific HTML elements and apply styles to them.

## CSS Selectors

CSS selectors are patterns used to select and style HTML elements. There are several types of selectors:

- **Element Selector**: Targets HTML elements by their element name.

  Example:
  ```css
  p {
    color: blue;
  }
  ```

- **Class Selector**: Targets elements with a specific class attribute.

  Example:
  ```css
  .highlight {
    background-color: yellow;
  }
  ```

- **ID Selector**: Targets a single element with a specific ID attribute.

  Example:
  ```css
  #header {
    font-size: 24px;
  }
  ```

- **Attribute Selector**: Targets elements with a specific attribute and value.

  Example:
  ```css
  [type="button"] {
    border: 2px solid gray;
  }
  ```

- **Pseudo-class Selector**: Targets elements based on their state or position.

  Example:
  ```css
  a:hover {
    text-decoration: underline;
  }
  ```

- **Pseudo-element Selector**: Targets a specific part of an element.

  Example:
  ```css
  p::first-line {
    font-weight: bold;
  }
  ```

## CSS Properties and Values

CSS properties define the visual style of HTML elements. Each property has a value that specifies how the style should be applied. Here are some common CSS properties:

- **color**: Sets the text color.
- **background-color**: Sets the background color.
- **font-size**: Sets the font size.
- **margin**: Sets the outer margin.
- **padding**: Sets the inner padding.
- **border**: Sets the border properties.
- **text-align**: Sets the text alignment.
- **display**: Defines the element's display type.
- **position**: Specifies the element's positioning method.

## Applying Styles to Elements

To apply styles to elements, you need to combine selectors with properties and values. Here's an example:

```css
/* Select all paragraphs with the class 'info' and change their font size and color */
p.info {
  font-size: 16px;
  color: #333;
}
```

In the next chapter, we'll explore the CSS Box Model, which is crucial for understanding layout and spacing in CSS.
```

You can copy and paste this Markdown content into your Markdown editor or platform to create Chapter 2 of your CSS crash course as an MD file.