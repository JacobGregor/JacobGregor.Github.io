## Article - 'The problem domain is the hardest part of programming'

Writing code is similar to that of solving the problem of a jigsaw puzzle.
1. Figure out what the main components of the problem are.
2. sort and build your component pieces. 
3. compile all of your component pieces. 
4. deploy the compiled components.

Programming is made easier when you understand the problem Domain. 

The more and more you strive to understand the problem the easier it is to solve that problem in code. Strive to articulately understand the question before trying to solve the problem. 

1. break your problem domain into parts rather than trying to solve the entire problem in one crack (components)

## **Chapter 3 - 'Object Literals' (pg. 100-105)

### What is an object? 
-> Objects group together variables to create a model.
- Variables are known as **'Properties'** Properties tell us about the object.
- Functions are known as **'Methods'** Methods are tasks that are associated with the object.

Like variables amd functions -> Properties and MEthods have a Name & Value associated with them. ( Key = Name, Value = Value)
- You cannot have two KEys w/ the same name in an object. 
- **Properties can have the value of 'String', 'number', 'boolean', 'array', or another object. Methods are always functions!**

Example Object:

``` javascript

var hotel {
  name: 'quay',
  rooms: 40;
  booked: 25;

  checkAvailability: function(){
    return this.rooms - this.booked;
  }
}

```
We have our declared Object (hotel). Inside we have established Properties (name,rooms,booked) and a Method (checkAvailability) which takes the values of rooms - booked to determine how many unbooked rooms there are. 

### Accessing Objects: Dot Notation

take the above example -> lets access the name and rooms property. 

`var hotelName = hotel.name;'
`var freeRooms = hotel.checkAvailability();'

Simple. we have a declared new variable to assign the value of what we are pulling from the object. in these to cases the value of hotel name and checkAvailability, 'quay' and '15' respectively. 

## **Chapter 5 - 'Document Object Model (DOM)'**

The DOM-Tree is a model of a webpage. 
Can layout this model w/ (Document, Element, Attribute and text 'Nodes' or bubbles)
(-> example of a DOM-Tree on pg. 187)

### Dom queries
- Methods that find elements in the DOM are called DOM queries. 
ex: 
`getelEmentById('element ID goes in here);`
-> to access this again, store as a var.
'var = elItem = getElementById(....);'

Methods that return Elements:
- `getElementById(....);
- `querySelector(CSS Selector);

- `getElementsByClassName(Class name here);
- `getElementsByTagName(Tag name here);`
- `querySelectorAll(CSS Selector);'

Selecting an Element from a Node-list (pg. 198-199);
- Item Method() example:
`var elements = document.getElementByClassName('hot')
if (element.length >= 1) {
  var firstitem = element.item(0);
}`

You can repeat actions through an entire NODELIST. (pg. 204 - 205);
-> pg 206 - 207 breakdown how a loopmthrough a nodelist functions. its syntax and how its applied in practice. 

Cross-Sire Scripting (XSS) -> pg. 228 - 229;

Attribute Nodes ex:
`document.getElementById('ID here).getAttribute(class here);` (pg. 232)






