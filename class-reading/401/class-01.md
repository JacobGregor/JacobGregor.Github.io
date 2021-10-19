# Reading #1

## Describe (in plain English) what Array.map() does.

`Array.map()` iterates through an array and applies a function to every element within that array and creates a new array out of the results of each iteration.

## Describe (in plain English) what Array.reduce() does.

`Reduce()` is going to take a `callback()` and apply that function to each element of an array. What makes `reduce()` different is its going to keep a running value applyiong the previous outcome to the current element until there are no more elements to apply, which will result in the final single value.

## Provide code snippets showing how to use superagent() to fetch data from a URL and log the result

`superagent.get( 'url here' )`

### With normal Promise .then() syntax

`superagent.get(http//:starwarsapi.com/people).then( result => { console.log(result.body); }); `

### Again with async / await syntax

`async function starWars() { let result = await superagent.get(http//:starwarsapi.com/people) console.log(result.body); };`

## Explain promises as though you were mentoring a Code 301 level student

This of Promises as a queue. you are going to make an ask for Javascript to doSomething() and you going to expect that once its done doing that thing it will return the results. Javascript is making a promise that once it can fulfil the request it will give you an answer, but it may not be right away. We need this because information may require multiple `callback()` functions to be performed before the data could be retrieved, leading to bottlenecks and what one website called 'Callback Hell', neerajnegi174 geeksforgeeks.com.

## Are all callback functions considered to be Asynchronous? Why or Why Not?

Here is a great explanation in my opinion, from author pspi on stackoverflow.com.  
"Simply taking a callback doesn't make a function asynchronous. There are many examples of functions that take a function argument but are not asynchronous,  
for example, Array's forEach.  
For a function to be asynchronous it needs to perform an asynchronous operation.

Ways of introducing asynchronicity can be

- timer functions setTimeout, setInterval
- special functions nextTick, setImmediate
- performing I/O (listening to network, querying a database, reading or writing from a resource)
- subscribing to an event

## Sources Used:

`reduce()`: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce  
`promises`: https://www.geeksforgeeks.org/javascript-promises/  
`callback()`: https://stackoverflow.com/questions/19083357/are-all-javascript-callbacks-asynchronous-if-not-how-do-i-know-which-are
