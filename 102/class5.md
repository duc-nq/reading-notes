# 05 - Design web pages with CSS

## What is the purpose of CSS?

**CSS (Cascading Style Sheets)** is used to style web pages and control the presentation of HTML elements on a website. It is a style sheet language that describes the layout, colors, fonts, and other visual aspects of a web page. CSS allows developers to separate the presentation of a web page from its content, making it easier to maintain and update the website. 

With CSS, developers can create responsive designs that adapt to different screen sizes and devices, and they can also create dynamic effects and animations to enhance the user experience.

## What are the three ways to insert CSS into your project?

1. **Inline CSS**: This method involves adding style attributes directly to HTML elements using the "style" attribute. For example, `<p style="color: blue;">This is a paragraph.</p>`.

2. **Internal CSS**: This method involves adding CSS styles within the head section of an HTML document, using the `<style>` tag.

3. **External CSS**: This method involves creating a separate CSS file and linking it to the HTML document using the `<link>` tag within the head section of the HTML document.

## Write an example of a CSS rule that would give all <p> elements red text.

An example of a CSS rule that would give all `<p>` elements red text:

p {
  color: red;
}

This CSS rule sets the color property of all `<p>` elements to red, which means that all paragraphs on the web page will have red text.