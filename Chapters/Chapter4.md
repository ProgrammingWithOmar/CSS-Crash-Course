
# Chapter 4: Typography

Typography plays a significant role in web design, impacting the readability and aesthetics of a website. In this chapter, we'll explore how CSS can be used to style text and fonts.

## Font Properties

CSS provides various font properties to control the appearance of text. Some important font properties include:

- **font-family**: Specifies the font to be used for text.
- **font-size**: Sets the size of the font.
- **font-weight**: Controls the thickness or boldness of the font.
- **font-style**: Defines the style of the font (e.g., italic).
- **font-variant**: Modifies the appearance of small-caps fonts.
- **line-height**: Sets the spacing between lines of text.

Here's an example of using font properties:

```css
/* Apply font properties to a paragraph */
p {
  font-family: "Arial", sans-serif;
  font-size: 16px;
  font-weight: bold;
  font-style: italic;
  line-height: 1.5;
}
```

## Text Alignment and Decoration

CSS provides properties for aligning text and adding decorative effects:

- **text-align**: Specifies the horizontal alignment of text (left, center, right, justify).
- **text-decoration**: Adds decorations to text (e.g., underline, overline, line-through).
- **text-transform**: Changes the capitalization of text (e.g., uppercase, lowercase, capitalize).
- **letter-spacing**: Adjusts the space between characters.
- **word-spacing**: Controls the space between words.

```css
/* Align text center and underline links */
p {
  text-align: center;
}

a {
  text-decoration: underline;
}
```

## Web Fonts

Web fonts allow you to use custom fonts in your web projects. You can include web fonts using the `@font-face` rule or by linking to external font libraries like Google Fonts. Here's an example of using Google Fonts:

```html
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open+Sans">
```

Then, apply the font in your CSS:

```css
/* Use the Open Sans font from Google Fonts */
body {
  font-family: "Open Sans", sans-serif;
}
```

## CSS Units for Typography

CSS offers various units to define font sizes and spacing, such as pixels (px), ems (em), percentages (%), and rem units. Each unit has its advantages and use cases. Understanding when to use each unit is crucial for responsive design.

## Practical Typography Examples

Let's explore practical examples of using typography in CSS:

1. **Creating Headings**:

   ```css
   /* Style headings with different font sizes and weights */
   h1 {
     font-size: 36px;
     font-weight: bold;
   }

   h2 {
     font-size: 24px;
     font-weight: normal;
   }
   ```

2. **Customizing Links**:

   ```css
   /* Style links with a custom font and color */
   a {
     font-family: "Arial", sans-serif;
     color: #0077cc;
   }
   ```

Typography is a crucial aspect of web design that can greatly influence user engagement and the overall look and feel of a website. In the next chapter, we'll explore colors and background styling with CSS.
```

You can copy and paste this Markdown content into your Markdown editor or platform to create Chapter 4 of your CSS crash course as an MD file.