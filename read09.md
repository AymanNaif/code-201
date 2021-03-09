# Forms and JS Events

### Forms:
An HTML form is used to collect user input. The user input is most often sent to a server for processing.

Form Controls:

1. adding text: text, password input, text area.

1. Making choices: such as radio button ,checkboxes ,Drop-down boxes .

1. Submititng forms: such as Subscribe , image, button .

### Form Structure:
`<form>` element should always carry the action attribute and will usually have a
method and id attribute too.

### actions: Its value is the URL for the page on the server that will receive the
information in the form when it is submitted.
###### Drop down list box
* we use for it (select) and we use an elememt inside the select element called (option) and it has an attribute value and selected.



###### File input cox
* we use for it (input) with attribut (type="file"). 


###### Image button
* we use for it (input) with attribut (type="image").

###### button and hidden controls
* button: The (button) element was introduced to allow users more control over how their buttons appear, and to allow other elements to appear inside the button.
* type="hidden" This example also shows a hidden form control.


###### Labelling Form Controls
* (label) When introducing form controls, the code was kept simple by indicating the purpose of each one in text next to it.
* (for): The for attribute states which form control  the label belongs to.Note how the radio buttons usethe id attribute.


###### Grouping Form Elements
* (fieldset) You can group related form controls together inside the (fieldset) element.
* (legend) The (legend) element can come directly after the opening (fieldset) tag and contains a caption which helps identify the purpose of that group of form controls.


##### HTML 5: Form Validation
* You have probably seen forms on the web that give users messages if the form control has not been filled in correctly; this is known as form validation.


##### HTML 5: Date Input
* we use for it (input) with attribut (type="date").


##### HTML 5: Email & URL Input
* email: we use for it (input) with attribut (type="email").
* URL: we use for it (input) with attribut (type="url").


##### HTML 5: Search Input
* we use for it (input) with attribut (type="search").


###### Placeholder
* On any text input, you can also use an attribute called placeholder whose value is text that will be shown in the text box until the user clicks in that area. Older browsers simply ignore this attribute.

### Lists, Tables and Forms

The **list-style-type** property
allows us to control the shape
or style of a bullet point (also
known as a marker).
It can be used on rules that
apply to the <*ol>*, <*ul>*, and <*li>*
elements.

**Unordered Lists**

For an unordered list we can use
the following values:
* none
* disc
* circle
* square

We can specify an image to act
as a bullet point using the
**list-style-image** property.
This property can be used on
rules that apply to the <*ul>* and
<*li>* elements.

Lists are indented into the page
by default and the **list-style-position**
property indicates
whether the marker should
appear on the inside or the
outside of the box containing the
main points.

**Table Properties**
* width to set the width of the
table
* padding to set the space
between the border of each table
cell and its content
* text-transform to convert the
content of the table headers to
uppercase
* letter-spacing, font-size
to add additional styling to the
content of the table headers
* background-color to change
the background color of the
alternating table rows


If we have empty cells in
our table, then we can use
the empty-cells property to
specify whether or not their
borders should be shown.

It can take one of three values:
* show
* hide
* inherit

**collapse**
Borders are collapsed into a
single border where possible.
(border-spacing will be
ignored and cells pushed
together, and empty-cells
properties will be ignored.)


## EVENTS 
When the user interacts with the HTML on a web page, there are three 
steps involved in getting it to trigger some JavaScript code. 
Together these steps are known as event handling. 

Select t he element 
node(s) you want the 
script to respond to. 

Indicate which event on 
the selected node(s) will 
trigger the response. 

State the code you want 
to run when the event 
occurs.
HTML EVENT HANDLER 
ATTRIBUTES (DO NOT USE) 

TRADITIONAL DOM 
EVENT HANDLERS
All modern browsers understand this way of creating an event handler, 
but you can only attach one function to each event handler. 

Event listeners are a more recent approach to handling events. 
They can deal with more than one function at a time 
but they are not supported in older browsers. 

##### THE EVENT OBJECT
    When an event occurs, the event object tells 
you information about the event, and the 
element it happened upon. 

Below you can see how you get the event object in IES-8. 
It is not passed automatically to event handler/listener functions; 
but it is available as a child of the window object. 

###### EVENT DELEGATION 

Creating event listeners for a lot of elements 
can slow down a page, but event flow allows 
you to listen for an event on a parent element. 


## USER INTERFACE EVENTS 

User interface CUI) events occur as a result of interaction with the 
browser window rather than the HTML page contained within it, 
e.g., a page having loaded or the browser window being resized.

### FOCUS & BLUR EVENTS 

The HTML elements you can interact with, such as links and form 
elements, can gain focus. These events fire when they gain or lose focus. 

##### MUTATION EVENTS &  OBSERVERS 
Whenever elements are added to or removed from the DOM, its 
structure changes. This change triggers a mutation event. 
