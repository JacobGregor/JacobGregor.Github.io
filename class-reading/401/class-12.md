### What is the benefit of transforming data into packets?

-> Speed. Packets have a faster byte transfer rate.

### UDP is often refereed to as a connectionless protocol. Why is this?

-> There is no beggining, middle ir end, data flows between the 2 systems continuously while streaming.\

### Can a socket server application have multiple socket connections?

yes.

### Can a socket connection application be connected to multiple socket servers?

yes.

### Can an application be both a socket server and a socket connection?

yes.

Definition:

Observer Pattern -> The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.\

Listener: An event listener waiting for the designated action to be fired, which will triger the resulting actions.\

Event Handler: A handler function used on event listeners that are triggered when the desired event action is fired. resulting in the desired actions to be handled.\

Event Driven Programming: In computer programming, event-driven programming is a programming paradigm in which the flow of the program is determined by events such as user actions (mouse clicks, key presses), sensor outputs, or message passing from other programs or threads.\

Event Loop: In computer science, the event loop is a programming construct or design pattern that waits for and dispatches events or messages in a program. The event loop works by making a request to some internal or external "event provider" (that generally blocks the request until an event has arrived), then calls the relevant event handler ("dispatches the event"). \

Call Stack: In computer science, a call stack is a stack data structure that stores information about the active subroutines of a computer program. This kind of stack is also known as an execution stack, program stack, control stack, run-time stack, or machine stack, and is often shortened to just "the stack".\

Emit/Raise/Trigger:
Emit: Emits a channel and a payload for .on functions to listen for.\
Raise:
Trigger: To fire an action or event which in-tern triggers a function call to perform a desired action.\

Subscribe: Listen/React to events from Emits.\

DataBase: Collection of storade data to be called upon by applications for use.\

sources:
https://en.wikipedia.org/wiki/Observer_pattern  
https://en.wikipedia.org/wiki/Event-driven_programming  
https://en.wikipedia.org/wiki/Event_loop  
https://en.wikipedia.org/wiki/Call_stack
