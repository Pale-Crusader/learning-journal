# CSS Class Notes and Reading

## Notes from Class
The terms which define what you're targeting is Selector
Within the curly braces are Declaration with Properties and their values

Selector and Declarations are a Ruleset

### Cascading Style Sheets
* reads top to bottom
* It matters where you place the rows and the last thing is what it finishes with. It allow you to changes all of something of a broad type into something and then a more specific target to change just that part.

### Box model
* padding
* border
* margin

### Color
* rgb code(red green blue)
* colors names
* hexadecimal code
* hsl (hue saturation lightness)

## Reading

CSS is for making webpages more attractive, and to control visual design. 

### Keys to Understanding CSS

* Imagine their is a box around each HTML element
* CSS allows you to create rules (as per rulesets above) to define how the box and its contents will look.
* <CSS Associates Style Rules with HTML Elements> Rules have two parts
    1.  the first part is the select and looks like the words used for the nesting within HTML
    2. the second part is the declaration which has two parts of its own
        1. The first part of a declaration is a property, which indicate what aspects of the element are to be affected, like font, color, shape, spacing with margin and width control
        2. the second part is the value which is how it is change. the easiest way to do this would be an example for a property of ```{background-color: yellow}``` yellow is what make the background yellow.


### Here is a very important note!
I am very glad to have this breakdown

``` <link href="css/sample.css" type="text/css" rel="stylesheet"> ```  
is an example pointing to a style sheet named sample.css in the css directory

#### This is the breakdown

* ``` <link> ``` is an element in HTML which can point to the css you want the browser to reference
* ``` href ``` specifics the path to the css
* ``` type ``` refers to what kind of document is being referenced
* ``` ref ``` defines the relationship between the HTMP page and the document so the browser knows what to do with it

### You can directly put CSS into an HTML page with the ``` <style> ``` element.