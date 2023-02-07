## Intro to CSS

### What is CSS?

CSS stands for cascading Style Sheets . CSS is how the the webpage looks to the users. Its the style/layout. 
 A **document** text file is made using  a markup laugauge like HTML.
 **Presenting** a document means showing the user the text file on a browser.
Broswers are sometimes called **user agents**.
CSS can be very basic ( changing font color and size ) or complex ( Creating side bars, columns, and even adding animation ). 



### CSS Syntax

CSS is a rule-based lanauage You set these rule by applying groups of sytle to elements or groups of elements.

Okay so Let's say we have a webpage with a Large Red Heading. the CSS styling should be:
    * H1 { color: red; Font-size: 5em; }

In that example the CSS rule open a **selector** which *selects* the HTML element we style. We know its a header by the "h1" .
Next is the { } which is a **curly brace**.
Inside of those braces will be **declarations**. This set the **property** and **vaule**. In this example the Property "color" and the Vaule of the Property is "red".
Another Declaration is this example is Font-size and that vaule is "5em".

CSS Properties have different vaules depending the property. The Color Property can only have color vaules. Font-size Property.

 ### CSS Modules 

CSS sytles everything on a webpage so its only right that CSS it brokedown in different modules. 

### CSS Specifications 

All Web Standards Technologies are defined in a giant Document call Specifications Which are published by standards organizations and define exactly how those  technologies are suppose  to Behave.
CSS is developed by a group in W3C , CSS Working group and they are constantly developing new features. (Tech is always changing ).

### Browser Support Information

Once a CSS feautre is Developed it is unlikely all browsers have implemented the feautre,(how the users on the page see the code) Therefore a Feature is only useful when it is picked by more than one browser and check the implementation status. Browser support status in shown on the MDN CSS Property page under a table called "Browser Compatibilty." With this you can check the requirments by choosing the compatibility table and check if the CSS feature is supoorted by the current browser. 

### Three Ways to Insert CSS

There are Three ways to insert CSS 

1. External CSS
    * With External CSS you can Change the look of the website with *one* file. Each HMTL page has have the reference to the external style sheet file inside the < link > element, Inside the head section.
    * An Example would be:
     < !DOCTYPE html > 
      < html > 
      < head >
      < link rel="stylesheet" href="mystyle.css" >
      < /head >
      < body >
      < h1 > This is a heading < /h1>
      < p> This is a Paragraph. < /p>
      < /body>
      < /html>
      * External CSS can be written in any text editior but has to be save with a .css extension. And it **Can Not** have any html tags.
      * The link in the example above should look like this:
      * body {
        background-color: lightblue;
      }
      h1 {
        color: navy;
        margin-left: 20px;
      }

**Note** Do not add spaces between the property value and the unit. i.e 20px


2. Internal CSS
    * Internal style is define inside the < style> element , in the head section
    * Example:
        < !DOCTYPE html>
        < html>
        < head>
        < style>
        body {
            background-color: linen; 
        }
        h1 {
            color: maroon;
            margin-left: 40px;
        }
        < /style>
        < /head>
        < body>

        < h1> this is a header< /h1>
        < p> This is a Paragraph.< /p>

        < /body>
        < /html> 

3. Inline CSS
    * Inline style may used to applly a unique style for a single element.
    * To use add the style attribute to the relevant element. The style attribute can contain any CSS property.
    * Example: 
         < !DOCTYPE html>
         < html>
         < body>
         < h1 style= "color:blue;text-align:center;"> This is a heading < /h1>
         < p style="color:red;">This is a paragraph.< /p>
         < /body>
         < /html>

**tip** Per article the Inline method isnt the best and doesnt have all the advantages of a style sheet and should be used sparingly.

### Multiple Style Sheets
If a property has defined the same selector in different style sheets, the value from the last sheet will be used. a Proprety may be defining the same header for example with 2 different color-vaules. The color on the last page will be used.  
The style element must be **after** the link to change the color-value.

### Cascading Order
All the styles in a page will cascade into a new virtual style sheet by the following rules, Number one being the highest priority.meaning that it will override the others

1. Inline style (inside an HTML Element)
2. External and Internal Style sheet (in the head section)
3. Browser default

### CSS Color Property

The color property tells the color of the text

CSS Syntax for color is " color|initial|inherit; those are the vaules 

* Color- specifes the text color
* Initial- set this property to its default value
* Inherit- Inherits this property from its parent element 

## Things I would like to know More About

1. "An internal style sheet may be used if one single HTML page has a unique style." not sure what that means?

2. Am i suppose to remeber the colorcodes?


