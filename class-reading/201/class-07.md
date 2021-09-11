## Article - 'Domain Modeling' 
- Introduction into Object-Oriented Programming.
-> A model that describes various entities, attributes and behavors all contained to fit the constraints of a problem domain. 
ex. 1 -> `Constructor function ()`
``` javaScript

var epicFailVideo = function(epicRating,hasAnimal) {
  var this.epicRating = epicRating;
  var this.hasAnimal = hasAnimal;
}

var parkourFail = new epicFailVideo(7, false);
var corgiFail = new epicFailVideo(4,true);


```
Above what we are doiong is **Instantiating**  `new epicFailVideo(....)` constructor functions by calling it with the `new` key and then initializing it with (parameters). **We now have 2 new instantated & initialized objects** that we are storing in the variables parkourFail & corgiFail respectively. 

### **Object Oriented Programming:**
1. The **`new`** keyword instantiates an object (creates)
2. the constructor function instantiates the object by using the &&this** variable.
3. The object is stores in variables to be used later.

### Concept introduction: 'Shared Code'

We create a new Method for the above example called generateRandom

``` javaScript
epicFailVideo.prototype.generateRandom = functiom (min,max){
  return Math.floor(Math.random() * (max-min +1) = min;

console.log(parkourFail.generateRandom(1,5));
console.log(corgiFail.generateRandom(1,5));

}
What happens here when we call the parkourFail & corgiFail variables is it surches its Methods to locate generateRandom. But its only 'true' methods are epicFailVideo... so after it searches all its defined methods it then looks through its 'prototype' methods. there it will find generateRandom which will then run. But when a 'Prototype' is shared between multiple objects it will run the code for all objects sharing that varible simultaniously, consuming less memory. This is important for Mobile.



```

## Chapter 6 - ' Tables' (HTML pg. 126-145); 
### Tables:
- Each block in a grid of a table is refffered to as a **Table-Cell**
Table Structure:
``` javaScript
<table> -> Table element is used to create the table
  <tr> -> Tr tag indicates the start of each row. closing the Tr tag closes the row. 
    <td>50</td> -> Each cell of a table is idicated with a Td tag. 
    <td>50</td>
    <td>50</td>
  </tr>
  <tr>
    <td>50</td>
    <td>50</td>
    <td>50</td>
  </tr>
  <tr>
    <td>50</td>
    <td>50</td>
    <td>50</td>
  </tr>
</table>

```
Table Structure (Introducing Headings)
```
<table> -> Table element is used to create the table
  <tr>
    <th></th> -> This will generate a blank heading giving us that indented heading look (pg. 132)
    <th scope='col'>Heading 1 </th> -> Vertical heading or Column heading. generated buy scope='col'
    <th scope='col>Heading 2 </th>
  </tr>
  <tr>
    <th scope='row'>Row 1 Heading (ex. boys</th> ->Horizontal heading or Row heading. generated buy scope='row'
    <td>jake</td>
    <td>mark</td>
  </tr>
  <tr>
    <th scope='row'>Row 2 Heading (ex. girls)</th>
    <td>sara</td>
    <td>jane</td>
  </tr>
</table>

```
You can **Span** a table entry across multiple columns or rows by incorporating the 
-> colspan='enter number of rows to span here' => ex. `<td colspan='2'> Geography</td>` geography will now span across 2 columns (horizontal)
-> rowspan='' will do the same but stretch down across a set number of rows. 

Reference (pg. 135 - 136) for a complete **Long Table** example. 
`<thead> </thead>` will create a top heading section to layout your headers of your table. it will then create a horizontal line under for seperation.
`<tbody></tbody>` will contain your `<tr>` (rows) tags and yuur `<td></td>`(cell data)
`<tfoot></tfoot>` will allow the same as the `<thead> element but create a seperate seperated section for the footer elements of the table. used in the example as a total of the 2 columns of the table. see example.

## Chapter 3 - 'Functions, Objects & Methods' 

### Functions

### **What is a Function?** - Functions group a series of statements together to perform a specific task. We can then **'Call'** these functions later to perform said task rather than repeating the same code. 
- What we pass through a function are known as `Function(**Parameters**)`
- What we get out of passing through our **parameters** is known as a **Return Value**. 

### **We call a Function this way:** 
`function helloWorld() {document.write('Hello World!');
}`
- Here we have a **Function Keyword** (function) followed by our **Function Name** (helloWorld()) with an empty parameters field.
- Inside the **Code Block** we are asking the function to write on the document 'Hello World' whenever we **Call** the function helloWorld().

### **Declaring a function(...)**
`function helloWorld(onomatopoeia) {
  return document.write(onomatopoeia + ' Hello World.') -> BANG! Hello World.
}
- We **declare** our parameters `function(**Parameters**` in the above example.
`let width = 3`
`let height = 5`
function calcArea(width, height) {
  return width * height;
}
- In this example we have set our **parameters** as 'width` & `height` but by passing through variables that hold the values we are now passing through what we call **Arguments**. 

-> Important examples of functions getting multiple values (width,depth,height) example on (pg. 95)

### **Objects***

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


