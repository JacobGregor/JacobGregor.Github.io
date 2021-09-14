## Things-I-Want-To-Know-More-About

## Reading-Notes

###Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
- Render.. Data flows in a single direction downward and therefore the render happens before componentDidMount.

###What is the very first thing to happen in the lifecycle of React?
Mounting -> Mounting, Updating and Unmounting are the three phases of the component lifecycle.

###Put the following things in the order that they happen:  **constructor**, **render**, **componentDidMount**, **React Updates** **componentWillUnmount**

###What does componentDidMount do?
THis allows anything to be loaded using a network request or DOM initialization. ex. Connecting to youtubes API and requesting a video.