# CSS Documentation 

## Introduction
CSS (Cascading Style Sheets) is a style sheet language used to describe the presentation of a document written in HTML. It defines how elements should be rendered on screen, paper, or in other media.

## CSS Syntax
CSS follows a specific syntax where styles are applied to elements using **selectors** and **declaration blocks**. The declaration block contains **properties** and **values** which define the styles for the elements.

---

## Including CSS in HTML
There are three ways to incorporate CSS into an HTML document:

1. **Inline CSS**: Applies CSS directly within an HTML element's `style` attribute.
2. **Internal CSS**: Embedded in the HTML file using the `<style>` tag inside the `<head>`.
3. **External CSS**: Linked as a separate `.css` file using the `<link>` tag.

---

## Color Properties
CSS provides properties to manipulate the color of elements:

- **color**: Sets the foreground (text) color.
- **background-color**: Defines the background color of an element.
- **Color Formats**: Can be defined using named colors, RGB values, hexadecimal codes

---

## CSS Selectors
CSS selectors are used to target HTML elements for styling:

- **Universal Selector (`*`)**: Selects all elements in the document.
- **Element Selector**: Selects all instances of a specific HTML element.
- **ID Selector (`#id`)**: Targets a single element with a specific `id` attribute.
- **Class Selector (`.class`)**: Targets elements with a specific `class` attribute.

---

## Text Properties
CSS provides a set of properties to control the appearance of text:

- **text-align**: Specifies horizontal alignment of text within an element.
- **font-weight**: Determines the thickness or boldness of the text.
- **text-decoration**: Adds effects like underline, overline, or strikethrough to text.
- **font-family**: Sets the typeface or font family for the text.
- **text-transform**: Controls capitalization and transformation of text.
- **line-height**: Defines the space between lines of text.
- **font-size**: Specifies the size of the text.

---

## Box Model
The **CSS Box Model** is a box that wraps around every HTML element. It consists of the following properties:

- **Content**: The actual content inside the box (text, images, etc.).
- **Padding**: Clears an area around the content (inside the border) 
- **Border**: Surrounds the padding and content.
- **Margin**: Clears an area outside the border.
  

  * Atribute related to Content
    - Width
    - Height 
  * Atributes related to padding
    - padding-left
    - padding-right
    - padding-top
    - padding-bottom
    - padding: top,right,bottom,left
  * Atributes related to margin
    - margin-left
    - margin-right
    - margin-top
    - margin-bottom
    - margin : top,right,bottom,left
  * Atribute related to Broder
    - Border-width
    - Baroder-style: solid/dotted/dash
    - Border-color
    - Border: width style color
    - Border-radius: 

The Box Model determines the element’s dimensions and space between elements.

---

## Display Properties
The **display** property controls how an element is displayed on the web page. Common display values include:

- **block**: The element takes up the entire width available, with a line break before and after.
- **inline**: The element takes up only as much width as it needs, without breaking the line.
- **inline-block**: Similar to `inline`, but allows setting `width` and `height`.
- **none**: The element is not displayed (removed from the document flow).

---

## Visibility
The **visibility** property determines whether an element is visible or hidden, while still occupying space in the layout.

- **visible**: The element is visible (default).
- **hidden**: The element is hidden, but space is still reserved.

## Positioning

### Position Property
The position CSS property defines how an element is positioned in the document. Common values include:

* static: The default positioning. The top, right, bottom, left, and z-index properties have no effect.
* relative: The element is positioned relative to its original position. The top, right, bottom, left, and z-index properties will work.
* absolute: Positioned relative to the nearest positioned ancestor. The element is removed from the document flow.
* fixed: Positioned relative to the browser window, staying in place when the page is scrolled.
* sticky: Positioned based on the user's scroll position.

#### Background Image : Used to set an image as background
* background-image : url("image.jpeg");
* background-size : cover / contain / auto

---
---
---
---
---



### PROJECT 01
##### PROBLEM STATEMENT
1. Create a simple div with an id "box".
* Add some text content inside the div.
* Set its background color to blue.
2. Create 3 headings with h1, h2 & h3.
* Give them all a class "heading" & set color of "heading" to red.
3. Create a button & set its background color to :
* green using css stylesheet
* blue using <style> tag
* pink using inline style
### PROJECT 02
##### PROBLEM STATEMENT
1. Create a heading centred on the page with all of its text capitalized by default.

2. Set the font family of all the content in the document to "Times New Roman".

3. Create one div inside another div.
* Set id & text "outer" for the first one & "inner" for the second one.
* Set the outer div text size to 25px & inner div text size to 10px.
### PROJECT 03
##### PROBLEM STATEMENT
* Create a Following Navbar

### PROJECT 04
##### PROBLEM STATEMENT
* Create a webpage layout with a header, a footer & a content area containing 3 divs.
Set the height & width of divs to 100px.
(add the previous navbar in the header)
* Add borders to all the divs.
* Give the content area an appropriate height.
* Add a different background color to each div with
