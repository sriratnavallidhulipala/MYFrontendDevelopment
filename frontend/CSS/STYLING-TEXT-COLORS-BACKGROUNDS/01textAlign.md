## Styling  Text,colors, and Backgrounds 
# Text Property 
- Text-align 
- Text-decoration 
- front-weight 
- front-family
- Line-height 
- Text-transform
## Text-Align property
- The primary purpose of the text-align property in CSS is to determine the alignment of text within an element.
- To center-align text within a block-level element,you should use the "center" value for the text-align property.
- The justify value for text-align is commonly used to create justified text,where both the left and right edges are aligned.
- The property used to align text vertically within an element in CSS is "vertical-align."
- the text-laign property controls the alignment of the inbline element itself when applied to inline elements within a paragraph.
- When you apply the text-align property to a parent element with multiple child elements, it will align all child elements based on the parent's value.
- If there is not enough space in a container for the specified alignemnt, the text will be wrapped to the next line.
- the value used to align text to the right in Css is "right"
- you can apply the text-align property to a specific HTML element in a css stylesheet by selecting the element using its tag,class,or ID in the CSS

- text-align :left /right/center
- text-align:center
- text-align:right
- text-align:left

## Text-decoration property
- The primary purpose of the Css property "Text-decoration" is to apply decorative effects to texy,such as underlines ot stikes.
- The CSS value "none" is used to remove any text decoration,such as underlines or strikes ,from text.
- you can apply an underline to text  using CSS with the property "text-decpration:underline;"
- The CSS property "text-decoration:line-through" strikes through the text with a horizontal line.
- The CSS property "text-decoration-color is used to control  the color of the text decoration,such sd underline or strike-through.
- you can apply a text decoration that appears over the text using CSS with the property "text-decoration:overline"
- The CSS property "text-decoration-style" allows you to specify the style of the text decoration,such as dotted or solid.
- In CSS,you would use "text-decoration:wavy;" to create a wavy underline for text.
- you can apply multiple text decorations to text in CSS by usinf a comma-sparated list,such as "text-decoration:underline,line-through;"
- The css property "text-decoration-width" is used to control the thickness or width of the text decoration lines,such as the underline
- text-decoratio:underline /overline/line-through
syntax
a:hover{text-decoration:none}
e.g a:hover{
    text-decoration:underline;
}

## FONT WEIGHT
- The CSS Property "font-weight" controls the font thickness or boldness of text.
- In CSS, you can set the font-weight property to "bold" to make text bold.
- the value "bold" for the font-weight" property makes text the boldest
- The default "font-weight" value for most text elements in CSS is "normal".
- you can set the font-weight to a value between normal & bold by using values like "500".
-  If a specific font does not have a bold variant, the font-weight" property applies a simulated bold style.
- The CSS property "font-weight" is used to define the thickness of fonts on a numeric scale.
- The value "normal" is typically used for text with a normal,regular thickness.
- In CSS, the font property can be used to set both the font-weight and the font-style in a single declaration.

 font-weight:normal/bold/bolder/lighter
 font-weight:100-90
 strong{
    font-weight:bold;
 }

# Font-family 
- The CSS property "font-family" is used to specify the font family for text within an HTML element
- Multiple font families in the "font-family" property in CSS are defined by separating them with commas.
- The "sans-serif" font family is typically specified as a fallback in case the desired font is not available on the user's device.
- In CSS, if you want to use a font family with spaces in its name,you should use double quotes("").
- The CSS property "font-weight" is used to define the weight or thickness of a font.
- The "serif" value in the font-family property typically represents fonts with traditional, elegant styles.
- The CSS property "font-size" is used to specify the size of the font.
- if a user's device does not have the specified font family, the browser will use the next specified font familt in the list.
- The CSS property font-style is used to control the slant or style of the font, such as italic or oblique.
- The CSS property "font-variant" is used to apply a font style that makes text appear in small caps.
- font-family:arial;
- font-family:arial,roboto
body{
    font-family:arial,sans-serif;
}

#  Line-height
- The CSS property "line-height"controls the spacing between lines of text.
- In CSS, the line-height property can be expressed in pixels as a percentage, or in em units
- When setting the line-height property to a value greater than 1 in CSS ,it increases,making the text more spaced out.
- The default value of the "line-height" property in CSS is 1.
- The purpose of adjusting the "line-height" property in CSS is to increase or decrease the spacing between lines of text.
- In CSS, a line-height value of 1 means single spacing,which is the default line height.
- you can set the line-height property in CSS for a specific element with the class text-block using the ".text-block" selector and specifying the desired line height value.
- When using "line-height" in CSS, the "%" unit represents a percentage of the font-size.
- Adjusting the line-height property can help improve the readability of text by affecting the line length & spacing between lines.
- When you set the line-height value to a number less than 1 in CSS,the lines are spaced closer together.

- line-height:2px
- line-height:3
- line-height:normal
e.g 
.spaced-text{
    line-height: 1.5;
}
# text-transform
- The CSS property used to adjust the spacing between characters in text is "letter-spacing",
- The CSS property used to make text appear in uppercase or lowercase letters in "text-transform
- The CSS property is used to set the alignment of text within an element is text-align
- The CSS property used to control the indentation of the first line in a block of text is "text-indent".
- The CSS property used to control the spacing between words in text us "word-spacing"
- The CSS text-transform property controls text capitalization and transformation 
- The "capitalize" value of the text-transform property capitalizes the first letter of each word.
- To convert all text to uppercase, you should use the "uppercase" value for text-transform.
- To prevent any text transformation with the text-transform property,you should use the none value.
- If you want to make all text lowercase,you should use the "lowercase" value for text-transform.
- The default value of the text-transform property is "none".
- You can apply the text-transform property to only a specific portion of text within an element by wrapping the text in a`<span>`element.
- The none value of the text-transform property is suitable for displaying text exactly as it appears in the HTML without any changes.
- In CSS, the text-transform property only affects the presentation of text, not the actual content of the HTML.
- to display an acronym in all uppearcase letters while keeping other text unchanged,you can use the "none" value for text-transform.

- Text-tranform :uppercase/lowercase/capitalize/none
e.g
.uppearcase-text{
    text-transform:uppercase;
}