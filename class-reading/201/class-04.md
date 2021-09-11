## **Chapter 4 - 'Links'**

How to write a link tag:
- `<a href="https://github.com/JacobGregor/JacobGregor.Github.io">Github</a>
-> Between `href= & > is where we place the link to our desired websitew or location. > between our carrots we place the name of what our user will click on to use the link. <
- `<a> </a> is our tag for links.
**Vocab**: When you link to external sites the link provided is acalled an **absolute** URL.
**Vocab**: When linking within your own file-tree the lionk used is a **Relative** URL -> ex. "index.html"

- Adding Email Links: `<a href="mailto:jake_gregor@icloud.com">Email Jake</a>`
- Linking to different parts of same page: `<a href="www.jakegregor.com/#top"> Top </a>` -> Link to 'Top' of webpage.

## **Chapter 15 - 'Layout'**

Block Level Elements: `<h1>, <p>, <ul>, <li>` -> Block levels start on a new line and act as building blocks for a webpage.

Inline Elements: `<img>, <b>, <i> -> flow between surrounding text. (pg. 361)

Containing Elements: If a block level elements is generated inside another block level elements the outer element becomes a **Container** or **Parent** element. 
-> a box may be nested inside several block-level elements, the Container is always the Direct parent of that element. 
### **Container Element:**
- `<div> </div>` -> we can group a number of elements inside a `<div>`. Ex. `<header> & <nav>` could make up the first `<div>` creating a menu bar with a header. 

### **Controlling the position of Elements**

Types of Positioning Elements:
- **Normal Flow**: Every Block-Level element appears on a new line. They will not sit next to eachother even if there is space.
- **Relative Positioning**: This moves an element "relatively" from its Normal positioned state. **Its relative to its natural position on the page, not relative to the page or any other elements.**
- **Absolute Positioning**: Allows for positioning in relation to its **Container**. It will not effect the position of any other elements as they will act as if the element in=s not there. (This is also how eleements stay there when we scroll).
- **Fixed Positioning**: Fixed position absolutely positions the element in relation to the **Browswer Window** and not the Container in whcih the element is housed, key distinction!
- **Floating Elements**: Allows you to take an element out of **Normal Flow** and position it to the right or left of the **COntainer**. Text will flow around this new **Block-Level** element.
### Examples of these are found on (pg. 365 - 370)

### **Page Sizes** -> (pg. 379 - 380)

### **Fixed & Liquid Layouts** -> (pg. 381 - 382)
-> Revisit this chapter to help create a nice liquid layout for your AboutMe page. 
-> pg. 387 -> talk about Grid Layouts and setting up a 'proper page'.

# **Javascript**

## **Chapter 3 - 'Functions, Methods and Objects'**
###What is a Function?** - Functions group a series of statements together to perform a specific task. We can then **'Call'** these functions later to perform said task rather than repeating the same code. 
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

## Article: '6 reasons for pair programming'

### 'How pair programming works'
- 'Driver' -> Driver is the programmer with his hands on the keyboard. Driver manages the text editor, switching files, version control.
- 'Navigator' -> Guides the driver through the inputs but does not write any code themselves. -> navigator can look up documentation, scan for bugs, plan out the algoritm but should never type themselves. 
- 4 basic skills to learning a language:
- Listening
- Speaking
- Reading
- Writing
-> Working in pair programming touches all of these.

6 advantages to pair programming:
1. Greater efficiency
2. Engaged collaboration
3. Learning from fellow students
4. Social skills
5. Job Interview Readiness
6. Work Environment Readiness 