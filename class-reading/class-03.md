# Readings: HTML Lists, Control Flow with js, and the CSS Box Model

## **Chapter 3 - 'Lists'**

**3 types of lists**
- Ordered Lists -> `<ol> </ol>`
- Unirdered list -> `<ul> </ul>`
- Defenition list -> `<dl> </dl>`

We use `<li>` tags within lists to create list items.
*Lists can be used inside of other lists to create **Nested Lists**

# **Chapter 13 - 'Boxes'**

## Important: By default a box is sized just big enough to hold its content.

### Box Dimensions

-> Create a `<div>` element and give it a height & width in css. 

### Min/Max Height & Width

-> Apply min and max settings to a box. this allows for dynamic movement of the box as the size of the available screewn changes. Used to ensure content isnt presented too narrowly.

### Padding
-> Spacing between your content and the border within ther box element your content is being displayed. 
- `Padding: (Top), (right), (bottom), (left);`

### Margin
- Controls the gap between properties.

# **Chapter 4 - 'Decisions and Loops'**

### Type Coercion
- Converts data behind the scenes to compute an operation
-> Used in weak languages (Like javascript)
-> Not used in Strong languages with require you to declare the type.

### Truthy and Falsy

**Falsy**:
-> Values that are treated as if they are false.
examples:
- `var = userName = 'false'`
- `var = userName = 0;`
- `var = userName = ''`
- `var = userName = 10/'score'`

**Truthy**
-> Values that are treated as true 
examples:
- `var = userName = true`
- `var = userName = 1;`
- `var = userName = 'carrot'`
- `var = userName = 10/5`

### **Loops**

3 kinds of loops:
- For Loops -> used for when you need to run code a specific amount of times. will continue to run until the condition counter is met.
- While Loops -> When you do not know how many times the condition needs to be run. This will continue until the condition parameter is no longer **true**
- Do While Loops -> Similar to the while loops except the do while loop will always run the statement inside the code block atleast once, even if the condition is **false**

example for loop:

`for (var i = 0; i < 10; i++) {
  document.getelementbyid('header')
};`
**More examples of loops found on pages 174 - 180**

