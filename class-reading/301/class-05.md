## Things-I-Want-To-Know-More-About  

## Reading-Notes  
Documentation -> Thinking in react  
https://reactjs.org/docs/thinking-in-react.html  

1. What is the single responsibility principle and how does it apply to components?  
-> What is sounds like, a component should only be responsible for handling a single task. If your component outgrows that principle it should be deconstructed into seperate components. The idea being reusability. We want components to handle single tasks so we can re-use them later in our application if need be. If a component is designed to several specific taks its not as transferable as its been built around a pre-existing situation. Keep this in mind.   


2. What does it mean to build a ‘static’ version of your application?  
-> Build a component heierarchy that simple passes data from Parent -> Child using props and not state. State allows for interactivity and we domnt want that in our static model. Essentially we are building a hard-coded wireframe of our website that has the bones of a connected hierarchical react app w/o the ability to alter data as a user.   


3. Once you have a static application, what do you need to add?  
-> Now we need to figure out the "Absolute minimal amount of state". We need to create state for our application by figuring out only what states need to created to allow for user interactivity and acheive our desipres API. this doesnt mean we cant ad more states later we just want to get the absolute minimum required.   
-> here are some questions for determining state:
1. Is it passed in from a parent via props? If so, it probably isn’t state.  
2. Does it remain unchanged over time? If so, it probably isn’t state.  
3. Can you compute it based on any other state or props in your component? If so, it isn’t state.  


4. How can you identify where state needs to live?   
Determining state:   
- Identify every component that renders something based on that state.  
- Find a common owner component (a single component above all the components that need the state in the hierarchy).  
- Either the common owner or another component higher up in the hierarchy should own the state.  
- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.  


Documentation -> Higher Order Functions  
1. What is a “higher-order function”?  
-> Essentially its a nested function. We can pass functions and parse over actions not just values. 
2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?  

`function greaterThan(n) {
  return m => m > n;
}
let greaterThan10 = greaterThan(10);
console.log(greaterThan10(11));
// → true`  

-> The greaterThan(n) function is taking in an argument of (n) and passing that argument into a return function that is returning a new value that is > than our input value. 

3. explain how either map or reduce operates, with regards to higher-order functions.  
We can map() through an input array and return a new array based on the input arguments or criteria set. from there we can use that return array for example within a setState() -> to update the state of our react application. (If we have a state: that is set to the origional state of the array being mapped.)