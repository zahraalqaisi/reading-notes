# the Duckett HTML book:

## Chapter 4: Ch.4 “Links”

***what is links?***

> Links are the defining feature of the web 
because they allow you to move from 
one web page to another — enabling the 
very idea of browsing or surfing.


***how to writing links?***

> Links are created using the <a> element. Users can click on anything 
between the opening <a> tag and the closing </a> tag. You specify 
which page you want to link to using the href attribute


### summary links:

-  Links are created using the <a> element.
- The <a> element uses the href attribute to indicate 
the page you are linking to.
- If you are linking to a page within your own site, it is 
best to use relative links rather than qualified URLs.
- You can create links to open email programs with an 
email address in the "to" field.
- You can use the id attribute to target elements within 
a page that can be linked to.

## Chapter 15: “Layout”:

***Key Concepts in 
Positioning Elements:***

- CSS treats each HTML element as if it is in its 
own box. This box will either be a block-level
box or an inline box.
   - Block-level elements
     start on a new line
   - Inline elements
     flow in between 
     surrounding text 

 - Containing Elements

 > If one block-level element sits inside another 
 block-level element then the outer box is 
 known as the containing or parent element. 

 - Controlling the 
 Position of Elements 

 > CSS has the following positioning schemes that allow you to control 
the layout of a page: normal flow, relative positioning, and absolute 
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.

- ormal flow
- Relative Positioning
- bsolute positioning

> To indicate where a box should be positioned, you may also need to use 
box offset properties to tell the browser how far from the top or bottom 
and left or right it should be placed. (You will meet these when we 
introduce the positioning schemes on the following pages.

- Fixed Positioning
- Floating Elements

***Screen Sizes***
> Different visitors to your site will have different sized screens that show 
different amounts of information, so your design needs to be able to 
work on a range of different sized screens.

***Screen Resolution***
> Resolution refers to the number of dots a screen shows per inch. Some 
devices have a higher resolution than desktop computers and most 
operating systems allow users to adjust the resolution of their screens.

***Page Sizes***
> Because screen sizes and display resolutions vary so much, web 
designers often try to create pages of around 960-1000 pixels wide 
(since most users will be able to see designs this wide on their screens).

***Fixed Width Layouts***
> Fixed width layout designs do not 
change size as the user increases 
or decreases the size of their 
browser window. Measurements tend 
to be given in pixels.

***Liquid Layouts***
> Liquid layout designs 
stretch and contract 
as the user increases 
or decreases the 
size of their browser 
window. They tend to 
use percentages.

### sammary layout:

- <div> elements are often used as containing elements 
to group together sections of a page.
- Browsers display pages in normal flow unless you 
specify relative, absolute, or fixed positioning.
- The float property moves content to the left or right 
of the page and can be used to create multi-column 
layouts. (Floated items require a defined width.)
- Pages can be fixed width or liquid (stretchy) layouts.
- Designers keep pages within 960-1000 pixels wide, 
and indicate what the site is about within the top 600 
pixels (to demonstrate its relevance without scrolling).
- Grids help create professional and flexible designs.
- CSS Frameworks provide rules for common tasks.
- You can include multiple CSS files in one page.

#  the Duckett JS book:

## Chapter 3 (first part): “Functions, Methods, and Objects”

### WHAT IS A FUNCTION?

***Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of st atements).***

### how we could write a function?

- ***declaring a function***
to create a function we give a name and then write the statement
needed ro achive its inside the curly braces 
- ***calling a function***
having declared the function we can then execute all fo statement between its curly braces with just one line code


### declaring function that need information

***in such cases when you declare the function you give is a parameters
inside the function the parameters act like variables***

### calling function that need information

***when you call a function that has a parameters you specify the values it should use in parantheses that follow its name the values are called arguments and any they can be provided as values or as variables***

### getting a single value out of a function 

***some function return information to the code that called them for example when they perform a calculation they return the result***

### GETTING MULTIPLE VALUES OUT OF A FUNCTION

***Functions can return more than one value using an array. For example, this function calculates the area and volume of a box.***

### creating an object: constructor notation

***the new keyword and the object constructor create a blank object 
you can then add properties and methods to the object***

### updating and object 

***to update the values of properties use dot notation or square bracket they work on objects created using literal or constructor notation to delete a property use delete keyword***

### CREATING MANY OBJECTS: CONSTRUCTOR NOTATION 

***Sometimes you will want several objects to represent similar things. Object constructors can use a function as a template for creating objects. First, create the template with the object's properties and methods.***













    
