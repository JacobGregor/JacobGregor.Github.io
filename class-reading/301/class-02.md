## Things-I-Want-To-Know-More-About

## Reading-Notes

###Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
- Render.. Data flows in a single direction downward and therefore the render happens before componentDidMount.

###What is the very first thing to happen in the lifecycle of React?
Mounting -> Mounting, Updating and Unmounting are the three phases of the component lifecycle.

###Put the following things in the order that they happen:  **constructor**, **render**, **componentDidMount**, **React Updates** **componentWillUnmount**

###What does componentDidMount do?
THis allows anything to be loaded using a network request or DOM initialization. ex. Connecting to youtubes API and requesting a video.

## Video Notes

What types of things can you pass in the props?
- Props can be thought of as arguments to a function.
- Counters, DOM to display to users, 
- the things you pass into a Class will be props for a component.

What is the big difference between props and state?
- High level -> Props you **pass into** a component, state is handled **inside** the component.
- State can be updated inside the component whereas props must be updated outside the component.
- Changing the state of the component will re-render the state of the component.
When do we re-render our application?
- Updating the state of the component will cause a re-render.
- **State is important for updating based on User data and input!**

- Think about where you are handling the data. If its inside the component and only inside USE STATE!
- Outside via a parent or the data is static and never going to change, USE PROPS!

What are some examples of things that we could store in state?
- Data inside a from that is updated by the User