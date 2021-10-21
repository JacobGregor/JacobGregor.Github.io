# Express REST API

### Name 3 real world use cases where you’d want to change the request with custom middleware

1. HTTPS -> HTTP redirect\
2. Improper /path requests\
3. TimeOut\

### True or false: The route handler is middleware?

False

### In what ways can a middleware function end the process and send data to the browser?

`Next();`\
`res.end();`\

### At what point in the request lifecycle can you “inject” middleware?

WRRC -> User sends a request to our server, `Server takes in the request` and `THEN runs Middleware`,`if(true){Next()} else{next('error')}`
What can cause express to error with “Request headers sent twice, cannot start a second response”
Calling a Callback twice
Making 2 request to the same /path

### Middleware - software that acts as a bridge between an operating system or database and applications, especially on a network.

### Request Object - Defines the resource that you wish to fetch.

### Response Object - An object defining a body for the response.

### Application Middleware - software that acts as a bridge between an operating system or database and applications, especially on a network.

### Routing Middleware - Middleware used for route managing.

### Test Driven Development - test driven development refers to a style of programming in which three activities are tightly interwoven.

### Behavioral Testing - a testing process for inputs in which you aren't writing the application.

### Sources:

https://developer.mozilla.org/en-US/docs/Web/API/Response/Response  
https://developer.mozilla.org/en-US/docs/Web/API/Request/Request

https://azure.microsoft.com/en-us/overview/what-is-middleware/
