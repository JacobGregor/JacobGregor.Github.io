### AWS: Cloud Servers

Describe the Web-Request-Response-Cycle
-> Client makes a request.  
-> Request hits our server  
-> Server then hits our Router  
-> Router handles any MiddleWare associated with the request (i.e Authentication or Authorization)  
-> request is processed  
-> response is handled and sent back to the Client  
-> response is rendered by the client.  
Explain what a “server” is, as it relates to the WRRC  
Our server is our middleman between our HTTP web requests coming from our client. The server houses our Routes and form our HTTP req/res cycle. The request comes into the server and the server routes the request to the avialable route based on the client request. The server handles the appropriate ations dictated by the request and han dles any authentiction/authorization along the process. the server then serves the response back to the client after getting the appropriate response from the HTTP request.

What does it mean to “deploy” an application?
Software deployment refers to the process of making the application work on a target device, whether it be a test server, production environment or a user's computer or mobile device.

Definitions:

Server:Our server is our middleman between our HTTP web requests coming from our client. The server houses our Routes and form our HTTP req/res cycle.  
Pub/Sub:
WRRC: The process of a CLient making a request to a server, who handles the appropriate request and serves a response back to the client. This is the HTTP req/res cycle.

sources:
https://www.codecademy.com/articles/request-response-cycle-static
https://backend.turing.edu/module2/lessons/how_the_web_works_http  
https://www.sumologic.com/glossary/software-deployment/
