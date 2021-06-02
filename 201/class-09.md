#  the Duckett HTML book:

## Chapter 7: “Forms” 

### what is forms ?

>  the term 'form' has referred to a printed document that contains spaces for you to fill in information.

### Why Forms?

> n addition to enabling users to 
search, forms also allow users 
to perform other functions 
online. You will see forms when registering as a member 
of a website, when shopping 
online, and when signing up for 
newsletters or mailing lists.

### How Forms Work??

1. A user fills in a form and then presses a button 
to submit the information to the server.

2. The name of each form 
control is sent to the 
server along with the 
value the user enters or 
selects.

3. The server processes 
the information using a 
programming language 
such as PHP, C#, VB.net, 
or Java. It may also store 
the information in a 
database.

4. The server creates a new 
page to send back to the 
browser based on the 
information received.

### sammury forms:

- Whenever you want to collect information from 
visitors you will need a form, which lives inside a 
<form> element.
- Information from a form is sent in name/value pairs.
- Each form control is given a name, and the text the 
user types in or the values of the options they select 
are sent to the server.
- HTML5 introduces new form elements which make it 
easier for visitors to fill in forms.

##Chapter 14: “Lists, Tables & Forms” 

- In addition to the CSS properties covered in other 
chapters which work with the contents of all elements, 
there are several others that are specifically used to 
control the appearance of lists, tables, and forms.
- List markers can be given different appearances 
using the list-style-type and list-style image 
properties.
- Table cells can have different borders and spacing in 
different browsers, but there are properties you can 
use to control them and make them more consistent. 
- Forms are easier to use if the form controls are 
vertically aligned using CSS.
- Forms benefit from styles that make them feel more 
interactive.

#  the Duckett JS book: 

## Chapter 6: “Events” 

### event flow 
> HTML elements nest inside other elements, if you hover or click on a link, you will also be hovering or clicking on its parent alaments 

### why flow matters??

> the flow of events only really matters when your code has event handlers on an element and one of its ancestor or descendant element 

### where events occur???

> the event object can tell you where the cursor was posioioned when an event was triggerd

### sammury events 
- Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked). 

- Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon. 

- When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user. 

- You can use event delegation to monitor for events that happen on all of the children of an element. 

- The most commonly used events are W3C DOM events, although there are others in  the HTMLS specification as well as browser-specific events. 
