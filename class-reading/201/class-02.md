# Readings: Basics of HTML, CSS & JS

## **Chapter 2 - 'Text'**

### **Key Concepts**
- Headings: we use h1 -> h6 tags. h1 being the largest header down to h6 being a small subheader.
- Paragraphs: p tags-> by default come with be determined styling applying new line spacing for each tag and space between each p tag.
- Bold: b /b: inline style
- Italic: i /i: Inline style
- superscripts: sup /sup: Inline styling
- subscripts: sub /sub: inline styling
- Line breaks: br /: will break you into a new line wherever you place this tag. 
- horizontal line rule: hr /: will create a horizontal line on the line where this tag is placed.

**Structural vs. Semantic Markup**
- **Structural**: Elements to describe headings and paragrapghs
- **Semantic**: provides information on the content w/ those elements. 

## **Chapter 10 - 'Inroducing CSS'**

### **Key Concepts**
*To Understand CSS think of every elements in HTML having an invisible box around it -> CSS allows us to manipulate these. 
Structurally we manipulate **Selectors** & **Declarations** to style elements. 
- P tags for example are selectors
- Background: grey; is a declaration. 
**Internal vs External CSS**
-> Just use external CSS..
How CSS hierachy works:
- Last Rule: if two selectors are identical the last one will take effect.
- Specificity: If one selector is more specific that one will take precidence. 

## **Chapter 2 - 'Basic Javascript Introduction**

### **Key Concepts**
**Sripts**: A series of instructions for a program to follow. 
**Variables**: A container to store information. Not Constant but can be redeclared without the use of var..

**Declaring a variable:** var (variable keyword) 'name of variable here' = 3; (Value of the variable)
- Data types: Numbers, Strings, Boolean, Undefined.

### **Arrays**
- Arrays are variables capable of storing a list of values. 

Example Array: var cats
               cats = [scotty, tom, jerry ]
-> Arrays start at the Zero for the first variable and go on for Array(Array name here).length -> ex. cats.length = 2


## **Chapter 4 - 'Decisions & Loops;**

2 Components of decisions:
1. and expressions evaluates and then returns a value.
2. conditionals are met -> do a given command.

**Everything that follows are conditonal statements**
**(Signs/Operators: Comparison Operators: pg. 150 - 151)**

- === -> both operends must be type strict to be **true**
- == -> does not need to be type strict to be **true**
- != -> is not equal to (not type strict)
- !== -> is not equal to (type strict)

**Comparison operators are made of 2 operands and 1 operator.**
- Operands do not have to be a single value ( 3 or 'three') we are also able to use stored variables as operends!

**Logical Operators**
-> Allow you to compare the results of more than one comparison operator
- && (Logical and) -> both operends must be true or else false
- || (logical or) -> one operend must be true or else false
- ! (logical not) -> inverts

**If statements**
-> evaluates the conditional (which we set in the parameters) and executes **if** the parameters are **true**.
If...Else statements work the same way except they execute the else code if the parameters set are not true. 

**Switch Statements**
Switch (...){
  
  case 1:
  name = Jake;
  break;

  case 2:
  name = bob;
  break;

  default:
  name = a girl has no name;
  break;

Unlike the If/Else statements a switch statement will run until a value is matched or the default is used in which case it will break; and stop running. Unlike an if/else statement that will continue to run even after a result is found if there are more conditions. 


}











