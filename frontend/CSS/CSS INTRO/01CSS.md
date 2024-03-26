### Basics of CSS
- CSS Stands for cascading stylesheets 
- the term "cascading" in CSS refers to the order of rule application & resolution in CSS.
- Primary purpose of CSS in web development is to control the representation and layout of web content.
- Css typically applied to Html elements By linking external css files to HTML documents.
- A CSS selector is a specific HTML element to which styles are applied.
- The CSS property color is commonly used to change the text color of an element
- The CSS margin property is used to add space between the border and content of an element.
- you  can include an inline CSS style within an HTML element by using the style attribue within the element.
- The CSS padding property is used to add space between the content and the element's border.
- CSS Pseudo-classes like:Hover and active are used to apply styles to elements when they are in a certain state.
- The cascading in cascading style sheet refers to the priority and order of applying styles to elements.
- CSS describes how HTML elements are to be displayed on screen,paper or in other media
- It can control the layout of multiple webpages all at once
- External stylesheets are stored in css files
- when there is a conflict between different css rules in the cascade,such as in the case of inline CSS and  external css ,it takes the most specific rule as precedence.
### Basic Syntax
## Selector
to design which element we add selector 
e.g `h1` `{
    color: red;
}
## property 
e.g heading element we need to add color,position,size,width,height 
## value 
e.g px,
### Inline css
- Inline Css within an HTML element using the style attribue.
- Inline CSS is applied directly to - individual HTML elements using the style attribute.
- particular element we are adding style i.e called inline css 
e.g`<p style="color:blue;">inline css</p>`
### Internal or Embedded CSS
- Internal CSS is typically placed inside the head section of the HTML document.
- we are coming into internal css because instead of adding the style many times we can  add it one time only inside the `<style>`container
- Inside the head tag we add CSS  code inside `<style>` tags.
- Embedded CSS is placed within the `<style>` element in the `<head>` section of an HTML document.
- In HTML,the `<style>` element is used to include CSS rules directly within the HTML document
- The role of the `<style>` element in HTML is to add internal css style to the HTML document
###  External CSS
- The purpose of linking an external CSS file to an HTML document is to apply styles and formatting to the HTML content.
- to link an external css file to an HTML document ,you use `<link>` element
- The type attribute commonly used for the `<link>` element when linking an external CSS file is "text/css".
- the "href" attribute in the `<link>` element specifies the path of the external CSS FILE
- The primary advantage of using external CSS is that it keeps the styles separate from the HTML content.
- In external CSS,the css code is typically stored in a separate .css file.
- External css is defined in separate CSS files with a.css extension. These CSS files are linked to HTML documents using the `<link>`element in the`<head>` section.

`<link rel="stylesheet" href="path/file.css">`
- For all html files with one css file we can use this external css.
- External CSS is commonly used for maintaining consistent styling across an entire website.
- The primary purpose of using an external CSS file instead of inline styles is to improve code readability

### Linking CSS to HTML
-  Linking External CSS(`<link>`)
How to create separate CSS File
Create a separate CSS file(e.g.,"styles.css") and define your styles within it
 # Steps:
 1. Create a CSS File
 2. Create an HTML Document
 3. Link the CSS File
 4. Place HTML content
 5. Save and Open