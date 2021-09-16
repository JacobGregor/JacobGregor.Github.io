## Things-I-Want-To-Know-More-About  

## Reading-Notes  
https://reactjs.org/docs/forms.html  -> Documentation.  

What is a ‘Controlled Component’?    
Its the idea of this “single source of truth”. We handle the state of the component within the component AND we adjust all subsequent changes to that state via user inout within the same component that then renders that state. The idea being that all user inout that effects that component is handled within that component making it 'controlled'.  

Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.    

I would assume that we should take the info as soon as we gather it so that we can update the state of our application and pass that information along to other components in our application if the data is needed.   

How do we target what the user is entering if we have an event handler on an input field?    
- We should State on our component equat to a value of ''.  
-> Setup a handleEvent(); that up setState() of our value: '' equal to the target value we are waiting for, in this case the input field.  
-> We would then pass this event into the <input> field of our form, which would update the state of our value based on user input.   

Documentation -> The Conditional Ternary Operator  
https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff  

Why would we use a ternary operator?  
- Its a way to write conditional if() in less lines of code. 
- More concise and easier to read.  
- same functionality as if();  
Rewrite the following statement using a ternary statement:
if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }

  `trueFalse () => x => x === y ? true : false`