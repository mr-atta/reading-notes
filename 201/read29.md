![EVENTS](https://www.edureka.co/blog/wp-content/uploads/2019/08/javascript-project.jpg)

# EVENTS (JS)

- **JavaScript's** interaction with HTML is handled through events that occur when the user or the browser manipulates a page. When the page loads, it is called an event. When the user clicks a button, that click too is an **event**.

### TERMINOLOGY

- FIRE OR ARE RAISED

  > When an event has occurred, it is often called having **fired** or been **raised**.

- EVENTS TRIGGER

  > Events are said to t rigger a function or script. When the click event fires on the element in this diagram, it could trigger a script that enlarges the selected item.

> ![EVENTS in JS](https://itzone.com.vn/wp-content/uploads/2019/06/Event-in-Javascript-1.png)

### There are so many different EVENT types you can use them in your code.

- MOUSE EVENTS , Occur when a user interacts with a mouse. trackpad, or touchscreen.

  - click : User presses a button over the same element
  - dbl click : User presses a button twice over the same element
  - moused own : User presses a mouse button while over an element
  - mouseup : User releases a mouse button while over an element
  - mousemove - mouseover - mouseout

- UI EVENTS , Occur when a user interacts with the browser's user interface (UI) rather than the web page.

  - load : Web page has finished loading
  - unload : Web page is unloading
  - error : Browser encountered an error
  - resize : Browser window has been resized
  - scroll : User scroll up or down the page

- KEYBOARD EVENTS , Occur when a user interacts with the keyboard.

  - keydown - keyup - keypress

- FOCUS EVENTS , Occur when an element (e.g., a link or form field) gains or loses focus
  - focus / focusin : Element gains focus
  - blur / focusout : Element loses focus
- FORM EVENTS , Occur when a user interacts with a form element
  - input - change - submit - reset - cut - copy - paste - select
- MUTATION EVENTS\* , Occur when the DOM structure has been changed by a script, To be replaced by mutation observers
  - DOMSubtreeModified - DOMNodelnserted - DOMNodeRemoved - OOMNodelnsertedlntoDocument - DOMNodeRemovedFromOocument

### HOW EVENTS TRIGGER JAVASCRIPT CODE

- there are three steps involved in getting it to trigger some JavaScript code:
  1. Select t he element node you want the script to respond to.
  2. Indicate which event on the selected node will trigger the response."binding"
  3. State the code you want to run when the event occurs.
- Together these steps are known as event handling.

![EVENT TO ELEMENT](https://slideplayer.com/slide/16904176/97/images/20/BINDING+AN+EVENT+TO+AN+ELEMENT.jpg)

## **THREE WAYS TO BIND AN EVENT TO AN ELEMENT**

1.  HTML EVENT HANDLER ATTRIBUTES

    - This approach is now considered bad practice.
      ![HTML EVENT HANDLER ATTRIBUTES](https://slideplayer.com/slide/16904176/97/images/23/HTML+EVENT+HANDLER+ATTRIBUTES+%28DO+NOT+USE%29.jpg)

2.  TRADITIONAL DOM EVENT HANDLERS

    - All modern browsers understand this way.
    - But you can only attach one function.
      ![TRADITIONAL DOM EVENT HANDLERS](https://slideplayer.com/slide/16904176/97/images/27/TRADITIONAL+DOM+EVENT+HANDLERS.jpg)

3.  USING DOM EVENT HANDLERS

    - If you use a named function when the event fires on your chosen DOM node, write that function first.
    - The DOM element node is stored in a variable. Here the text input (whose id attribute has a va lue of username) is placed into a variable called e 1 Username.

## EVENT LISTENERS

![EVENT LISTENERS](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQppneRzV6jeunvpVRzWQEBOx1MFQdSq7efPg&usqp=CAU)

### **What Are Event Listeners?**

> Event listeners are among the most frequently used JavaScript structures in web design. They allow us to add interactive functionality to HTML elements by “listening” to different events that take place on the page, such as when the user clicks a button, presses a key, or when an element loads.

- Adds an event listener to the DOM element node
  ![Add event listener to DOM](https://slidetodoc.com/presentation_image/136f5d765d0686d925d0c3c7e2c96a57/image-33.jpg)

## Event Flow

- Event flow : is the order in which event is received on the web page. If you click on an element like on div or on the button , which is nested to other elements, before the click is performed on the target element.

  - Determine the objective.
  - Organize a team.
  - Set a date.
  - Create a plan.
    ![Event Flow](https://www.javascripttutorial.net/wp-content/uploads/2020/02/JavaScript-DOM-Level-2-Event.png)

### DIFFERENT TYPES OF EVENTS

- Events are defined in:
  - The W3C DOM specification
  - The HTMLS specification
  - In Browser Object Models

### LOAD

- The load event is commonly used to trigger scripts that access the contents of the page. In this example, a function called setup() gives focus to the text input when the page has loaded.
  ![LOAD](https://cdn.devdojo.com/posts/images/November2018/get-a-preloader-on-your-site-with-jquery.jpg?w=1280&h=720&fit=crop)

# Form (HTML)

![Form](https://i.ytimg.com/vi/D4jj3HHrnSU/maxresdefault.jpg)

- An HTML form is used to collect user input. The user input is most often sent to a server for processing.
- `<form>`

#### ADDING TEXT:

- Text input (single-line)
- Password input
- Text area (multi-line)

#### Making Choices:

- Radio buttons
- Checkboxes
- Drop-down boxes

#### Submitting Forms:

- Submit buttons
- Image buttons

#### Uploading Files:

- File upload

## How Forms Work ??

![Forms](https://www.researchgate.net/profile/Amer-Elameer/publication/321708049/figure/fig15/AS:569702479269890@1512839063713/Figure-2-12-How-Forms-Work11.png)

- The `<form>` element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.
- The HTML `<input>` element is the most used form element.
- An `<input>` element can be displayed in many ways, depending on the type attribute.
  ![Form](https://i.ytimg.com/vi/XDKlzbgFcG8/maxresdefault.jpg)
- Notice the use of the `<label>` element in the example above.

### Drop Down List Box

- `<select>` , A drop down list box (also known as a select box) allows users to select one option from a drop down list.

## Summary

- Whenever you want to c XX ollect information from visitors you will need a form, which lives inside a `<form>` element.
- Information from a form is sent in name/value pairs.
- Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.
- HTML5 introduces new form elements which make it easier for visitors to fill in forms.
