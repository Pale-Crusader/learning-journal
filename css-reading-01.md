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

#### This is the breakdown to use a CSS sheet.

* ``` <link> ``` is an element in HTML which can point to the css you want the browser to reference
* ``` href ``` specifics the path to the css
* ``` type ``` refers to what kind of document is being referenced
* ``` ref ``` defines the relationship between the HTMP page and the document so the browser knows what to do with it

#### Why external style sheets?
* all your pages can share a css style sheet leading to vidual consistency
* after first looking at the page the end user will have a faster experience because the css is already downloaded
* Allows you to reuse the CSS sheet for multiple pages so you don't have to re-enter or copy paste it into each page making changes centralized and faster

#### Why not?
* Might be overkill for a simple single page site
* It still might be better to use it
* 


### You can directly put CSS into an HTML page with the ``` <style> ``` element in the head. The CSS code goes within the style tag.

### You can also do inline, is is done as attributes of the element which overrides CSS because it is applied last

CSS rules casade as described in class notes above. Additionally !important after a property to indicate it should be considered more important than other rules.



## More Notes
Not called order of operations, it is the casading effect because specificity and inheritance are also vital to the topic. Essentially things are inherited via the parent/child nesting within HTML

```id``` are specific to a __SINGLE__ element, otherwise it break, and allow you to pick them out speficially

```class``` is like id but allows you to do multiple

when selecting with an id or class use a hashtag and then the name as the root selector example for my class which has a ```class="plane-truck"```
```#plane-truck```

Float property changes the flow of the page

adding a . with a space and then a class name allows you to select them like the hastag for id
Changing margins moves things the way the margin isn't
border needs to be commanded in css to show on the page, it  doesn't show by default

```main article {display: inline; width: 33%;}``` 
```a: hover {color: auqua}```
```{text-decoration: none}``` for li of links

are things I want for my project page.

You can define values for margins right top left bottom within a single line

There are specific properties for the different sides of margins also

width hieght are properties which can be defined

Test changing the side of the page will help test the flow of elements, for troubleshooting.

If a class is a parent the children of that class are put after the . and class name

```reset.css``` allows overwriting the browser default formatting

a: hover {color: auqua}