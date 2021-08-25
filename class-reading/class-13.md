## Local Storage 
In its most basic form Local storage is a way to store key/value pairs localy within the client web browser. The data is never transmitted to a remote web server unlike cookies, yet like cookies the data persists on page refresh and browser close. 

Checking for HTML5 Local Storage:

`function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}
Instead of writing this function yourself, you can use Modernizr to detect support for HTML5 Storage.

if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
}`
data is stores using **Key/Value** pairs. Data is stored with a **Key** and then retrieved by the same **Key**. 

### Important Notes: 

1. Keys are stored as strings, the data can be any type however it will always be returned as a string and therefor must be converted to numbers using `parsInt();` or `parseFloat()`. 

2. Calling `setItem()` with a named key that already exists will silently overwrite the previous value. Calling `getItem()` with a non-existent key will return null rather than throw an exception.


### setting a Key/Value Pair

3. Like other JavaScript objects, you can treat the localStorage object as an associative array. Instead of using the `getItem()` and `setItem()` methods, you can simply use square brackets. For example, this snippet of code:

`var foo = localStorage.getItem("bar");
// ...
localStorage.setItem("bar", foo);
…could be rewritten to use square bracket syntax instead:

var foo = localStorage["bar"];
// ...
localStorage["bar"] = foo;`

### Removing values for a key

`interface Storage {
  deleter void removeItem(in DOMString key);
  void clear();
};`

calling `removeItem()` with a non-existent key will do nothing. 

### to iterate through the total number of values in the storage area:
   
   `interface Storage {
     readonly attribute unsigned long length;
     getter DOMString key(in unsigned long index);
   };
   calling key() with an index not between 0-(length) you will get back null.
