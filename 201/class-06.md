#  the Duckett JS book:

## Chapter 3: “Object Literals”

### WHAT IS AN OBJECT?

***Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names***


### creating an object : literal notation:

***literal notation is the easiest and most papular way to create objects the object is the curly braces and their contantand it is stored in a var. called hotel***

### accesing an object and dot nototion:

***you access the properties and the mathods of an object using dot notation you can olso access properties using square pracket***

### creating an object constructor notation

***the new keyword and the object constructor create a blank object you can then add properties and methods to the object ***

### updating the object :

***to update the value of properties use dot notation or square brecket they work on objects created using litaral or constructor notation
to delete a propety use the delete keuword***


### CREATING MANY OBJECTS: CONSTRUCTOR NOTATION 

***Sometimes you will want several objects to represent similar things. Object constructors can use a function as a template for creating objects. First, create the template with the object's properties and methods***

### arrays are object 

***they hold a related set of key/value pairs (like all objects) but the key for each value is its an index number***


### arrays of object and object in arrays :

*** you can combine arrays and object to create complex data sutrcture arrays can store a series of object and object can also hold arrays .


## Chapter 5: “Document Object Model” 

### caching dom queries:

***methods that find elements in the dom tree arw called dom queries when you need to work with an element more than once you should use a variable to store the result of this query***

### methods that select individual elements:

***getElementById() and querySelector() can both search an entire document and return individual elements both use a similar syntax***

### select an element from a nodelist

***there are two ways to select an element from a nodelist:***
- the item() method 
- array syntax
> both require the index number of the element you want

### repeting actions for an entire nodelist 

***when you have a nodelist you can loop through each node in the collection and apply the same statments to each***

### adding or removing htmt content:

***there are 2 different approaches to adding and removing content from a dom tree***
- the innerHTML proprty
- dom manipulation

### attribute nodrs 

***once you have an element node you can use other properties and methods on that element node to access and change its attributes***


### summary document object model


- The browser represents the page using a DOM tree. 

- DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes.

- You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax.

- Whenever a DOM query can return more than one node, it will always return a Nadel i st.

- From an element node, you can access and update its content using properties such as textContent and i nnerHTML or using DOM manipulation techniques. 

- An element node can contain multiple text nodes and child elements that are siblings of each other. 

- In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery). 

- Browsers offer tools for viewing the DOM tree . 