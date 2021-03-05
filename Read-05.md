#  Images, Color, Text

## HTML: (chapter 5: Images)

### Choosing Images for Your Site
#### Images should :
- #### Be relevant
- #### Convey information
- #### Convey the right mood
- #### Be instantly recognisable
- #### Fit the color palette

### Storing Images on Your Site
#### if you are building a site from scratch, it is good practice to create a folder for all of the images the site uses.

### Adding Images
#### To add an image into the page you need to use an <img> element. This is an empty element (which means there is no closing tag). It must carry the following two attributes:
- #### src : This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site.
- #### alt : This provides a text description of the image which describes the image if you cannot see it.
- #### title : You can also use the title attribute with the <img> element to provide additional information about the image.

### Height & Width of Images 
- #### height : This specifies the height of the image in pixels.
- #### width : This specifies the width of the image in pixels.

### Where to Place Images in Your Code
1. #### before a paragraph
2. #### inside the start of a paragraph
3. #### in the middle of a paragraph

### Three Rules for Creating Images
1. #### Save images in the right format
2. #### Save images at the right size
3. #### Use the correct resolution

### image format
![image format](https://img.pagecloud.com/wAegMZSQrxtIBtV-i7jBCW-Ho7Y=/1000x0/filters:no_upscale()/blogmerge/cf67f56e-00e6-48c0-a1a4-31a8e3baf0de.jpeg)

### HTML 5: Figure and Figure Caption
#### Images often come with captions. HTML5 has introduced a new <figure> element to contain images and their caption  so that the two are associated
#### The <figcaption> element has been added to HTML5 in order to allow web page authors to add a caption to an image

![image](https://user-images.githubusercontent.com/79092103/110122447-505aef00-7dc8-11eb-993f-da07eddb9cdd.png)

## chapter 11 ( color )

####  is a style sheet language used for describing the presentation of a document written in a markup language such as HTML.
#### to understanding how CSS works is to imagine that there is an invisible box around every HTML element.
#### CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface

#### CSS works by associating rules with HTML elements. The rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.

## CSS Rules
### it have a very big library that you can use to know , just check out [w3school](https://www.w3schools.com/w3css/defaulT.asp)

# Color can really bring your pages to life

## Foreground Color
#### The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:
* #### rgb values
#### These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)
* #### hex codes
#### These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80
* #### color names
#### There are 147 predefined color names that are recognized by browsers. For example: DarkCyan We look at these three different ways of specifying colors on thenext double-page spread.
## Understanding the color
#### Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker. Understanding Color Computer monitors are made up of thousands of tiny squares called pixels (if you look veryclosely at your monitor you should be able to see them). When the screen is not turned on, it's black because it's not  emitting any light. When it's on, each pixel can be a differentcolor, creating a picture. The color of every pixel on the screen is expressed in terms of  a mix of red, green, and blue â€” just like on a television screen. Color picking tools are available in image editing programs like Photoshop and GIMP. You can see the RGB values specified next to the radio buttons that say R, G, B. The hex value is provided next to the pound or hash # symbol. There is also agood color picking tool at: [colorschemedesigner](https://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF)

## Contrast
#### When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible

## CSS 3: Opacity
#### The CSS3 rgba property allows you to specify a color, just like you would with an RGB value, but adds a fourth value to indicate opacity. This value is known as an alpha value and is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacityand 0.15 is 15% opacity). The rgba value will only affect the element on which it is applied (not child elements)

## CSS 3: HSL Colors
#### CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation, and lightness values

## CSS 3: HSL & HSLA
#### The hsla color property allows you to specify color properties using hue, saturation, and lightness as above, and adds a fourth value which represents transparency (just like the rgba property).
