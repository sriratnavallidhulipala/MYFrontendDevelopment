## Background Properties
 - Background color property 
 - Background Image property 
 - Background-Repeat property
 - Background Size property 
 - Background position property 
 - Background shorthand property

 ##  Background-color property 
 - The primary purpose of the CSS background-color property is to set the background color of an HTML ELEMENT.
 - In CSS, you specify a color for the background-color property with a color name like "red" or "blue"
 - The CSS property used to define the background color for an HTML element is "background-color".
 - Setting the background-color property to transparent makes the element's background fully transparent
 - The value used to specify a transparent background in CSS is transparent
 - The default background color of an HTML webpage,when the background-color property is not set,it typically white.
 - colors can be represented using hexadeciaml values in the background-color property with a pound sign(#) followed by six characters.
 - The CSS property that allows you to add a background image to an element is "background-image".
 - When you sey the background-color to inherit in CSS it takes the background color from the parent element.
 - The CSS background-color property is used in web design for setting the color of an element's background.
 
-  Used to set the color of the background 
 body{
    background-color:lightGreen;
 }
## Background Iamge Property
- The CSS background-image property is used for setting an image as the background for an element 
- The background-image property in CSS is typically written as "background-image:url(image.png)
- The URL inside the background-image property typically points to the background image file to be used.
- In CSS,"NONE" is used to specify that no background image should be displayed.
- To Set a background image to repeat both horizontally and vertically in CSS,you use "backgrounf-repeat:repeat";
- The CSS property used to control the positioning of the background image within an element is "background-position."
- The default value of the background-position property,if not specified, is "top left".
- To make a background image fixed so that it doesn't scroll with the content,you use background-attachment:fixed";
- The CSS property used to control the size of the background image is "background-size",
- The CSS property that allows you to combine multiple background images for an element is "background"

## Background-Repeat property
- The CSS background-repeat property is used to control how a background image is repeated or tiled.
-  The "no-repeat"value of the background-repeat property ensures that the background image is not repeated.
- if no value is specified for the background-repeat property, the default behavior is to "repeat". the background image.
- "repeat-x" means that the background image is only repeated horizontally.
- "background-repeat:repeat-y" means that the background image is repeated vertically only.
- To sepcify that a background image should repeat only in a horizontal direction,you use "background-repeat:repeat-x".
- The CSS property used to specify the starting position of a backgroynd image in conjuction with background-repeat is "background-position"
-  To make a background image repeat in both horizontal and vertical directions you should use the value "repeat".
- The CSS property "background-attachment" is used to ensure that a background image is fixed in place while the content scrolls.
- When you set "background-repeat:repeat-x" and the content's height exceeds the height of the background image , the image will repeat both horizontally and vertically.
- The background-repeat property repeats an image both horizontally and vertically.
- background-repeat:repeat-x/repeat-y/no-repeat
e.g       {
            background-repeat: repeat-x;
            background-repeat: repeat-y; 
            background-repeat: no-repeat;
            }

## Background Size property 
- The primary purpose of the CSS background size property is to control the size of a background image.
- You can specify a specific size for a background image using "background-size:100%;" in css
- the cover value of background-size scales the background image to cover the entire element,potentially cropping parts of the image.
- To scale the background image to fit the entire element without cropping,you should use "contain" for background-size.
- The "auto" value of background-size automatically adjusts the background image to its original size.
- When using the background-size property with two values represent the width and height of the background image.
- To make a background image repeat both horizontally and vertically to fill the entire element, you should set "background-repeat:repeat";
- The default value of the background-size property is "auto" if not explicitly specified.
- When a backgrounf image is set to repeat both horizontally and vertically,"background-size" has no effect on repeated background images.
- In CSS, you can use "percent(%)" as a unit of measurement with background-size to specify the size of the background image.

- The background-size property specifies the size of the  background image.
- background-size:cover/contain/auto
e.g
size{
          background-image: url("./html.png");
          background-repeat: no-repeat;
          background-size:300px 100px;
        }

 ## Background position property
 - The CSS background position property controls the alignment of the background image.
 - Common values to define the horizontal position of a background image are "left,center,right"
 - "Center center" is avalid value for centering the background image both horizontally and vertically
 - To position the background image at the top right corner,you should use "top right" as the background-position values.
 - The default value for the background property in CSS,if not specidied , is "top left".
 - The background" property can be used in shorthand format to set the background image's position along with other background properties.
 -    When using percentage values in the background-position property,it measures the values against the width and height of the containing element.
 - "left bottom" would position the background image at the bottom left corner of its containing element.
 - If you specify only one value for background-position(e.g center) the background image will be created both horizontally and vertically 
 - you can set the horizontal and vertical background positions separately in the shorthand background property by using "background-position-x" and "background-position-y"
 
 - background-position:left/top/center/bottom/right;
 - e.g
 img{
   background-position:left;
 } 
 ## Bakground position property 
 it will be fixed or scrolled

 ## Background shorthand property
 background:[background-color][background-image] [background-repeat] [background-attachment] [background-position];
 - The CSS background shorthand property allows you to set the background color of an element.
 - The "background-color" property is used to set the background color of an element in the background shorthand.
 - The primary purpose of the "background-image" property in the background shorthand is to specify an image for the background.
 - The "background-repeat" property controls whether a background image repeats vertically ,horizontally,both or not at all.
 - To specify that a background image should not repeat at all,you use "background-repeat:no-repeat" in background shorthand.
 - The "background-position" property in the background shorthand determines the position of the background image.
 - The "background-attachement" property controls whether the background image scrolls with the content or stays fixed in place.
- syntax "background:image-size repeat color".
- "background-color"should comes first in the declaration
- The "cover" value is used to set the size of the background image in the background shorthand property.
