# read 5
Contents:
1. what is css.
2. colors.
## css 
css allows us to present what we structured in HTML and it make our website more attractive.the latest version of css is 3
## css rules
**you should apply CSS in seprate style sheet to apply the code in all your pages**

## adjust colore. colores helps  X convey the mood and evokes reactions.

*There are three ways to specify colors in CSS*:  X RGB values, hex codes, and color names.ss

* you can change the background color for each part by writing this code: body { background-color: rgb(200,200,200);}
* you can specify color properties using hue, saturation, and lightness as above, and adds a fourth value which represents transparency (just like the rgba property) by: body { background-color: #C8C8C8; background-color: hsl(0,0%,78%);} 

### example
* The rule for the <body> element sets a default color for all the text as well as the default background color for the page. Both use color names.
* The rule for the h1 element sets the color of the heading using a hex code. There are two values for the background-color property of the <h1> element. The first provides a fallback color using a hex code and the second is an HSLA value for browsers that support this method.
Each paragraph is then shown in a different color to represent the varying levels of acidity or alkalinity, and these are specified using RGB values.
* The example also uses a property called margin to decrease the gap between the paragraph boxes, and a property called padding to create a gap between the edge of the boxes and the text within them.


 ### examples:
  body {    background-color: silver;}
  h1 {    background-color: #ffffff;    background-color: hsla(0,100%,100%,0.5);    color: #64645A;}
   p.zero {    background-color: rgb(238,62,128);}  
   p.one {    background-color: rgb(244,90,139);}
   <p class="fourteen">14.0 VERY ALKALINE</p> 
   <p class="thirteen">13.0</p