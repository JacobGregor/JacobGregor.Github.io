## Chapter 7 - 'Forms'
we will be storing data in forms using 'Name value pairs"
structure: 
`<form action="URL where the form will send its data" methord='get or post'
    <p> This is where the form controls will go</p?
</form>`
Methods on forms: We have the "Get" and "Post" Methods.
- Get: we will use get when we are just trying to "get" information from the web server. we will not use this if we are adding or removing information from the database.
- Post: Use post if you are allowing your uuser to upload files, contains sensative data or adds to or deletes information from the database.

## Chapter 14 - 'Lists, tables & Forms' 
A lot of perviously discussed CSS styling properties are the same properties that work to style our Lists, Forms and Tables. There are however element specific css styling tools. Examples are "list-style" and "list-style-position", "empty-cells and "border-spacing".
We are able to maipulate the CSS of Table cells to keep consistency across different browser widows. creating a more fluent product. 
-> Forms are easier and more maniuplated when they are vertically aligned. 

### **JavaScript**

## Chapter 6 - 'Events" 
Terminology: 
- When an event occurs industry standard termonology is to refer to the event as having **Fired**. 
-> when an event fires it **Triggers** an event which triggers a script to execute. 

Many ddifferent types of events: 
- UI Events;
- Keyboard Events;
- Mouse Events;
- Focus Events;
- Form Events;
- Mutation Events;

### Event Handling
1. Select the **element** node you want the script to respond to.
2. Indicate which **event** on the selected node will trigger the response
3. state the **code** you want to run when the event occurs.

Ex. 
1. Event: blur on username(DOM element)
2. when the user is done interacting with the username it will fire the blur event.
3. when the blur event fires it will trigger our code `username()`.
4. Based on what our script does it will be evaluated. 

### Event handlers & Event Listners
**Syntax**
Event Handler: `element.event=functionName;`
Event Listener: `element.addEventListener('event', functionName, boolean);`

### Event Objects (pg. 262-263)
when an event occurs, the event object tells you informtion about the event and the element it happened on. 
Go back and reviews Events pages (280-290); 