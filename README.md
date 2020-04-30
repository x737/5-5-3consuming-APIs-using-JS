# Consuming APIs using JavaScript

## xhr (index.html and main.js)

xhr allows us to call external APIs from our Javascript application
by instantiating the **XMLHttpRequest** object

XMLHttpRequest object is an inbuilt object that JavaScript provides to allow us to consume APIs.
this gives us the method to open connections, to send connections, and close them.

+ XML stands for Extensible Markup Language
+ then it comes to the xhr.open() method, and the first argument that we parse in is "GET".
+ The GET method is used when we're retrieving data from the server, here get api from swapi
+ POST method is used when we're sending data to the server, such as an uploaded file or form data.
+ The xhr object maintains <a href="https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/readyState">an internal state</a> as it's completing various parts of our request operation. And "readyState = 4" means that the operation has been completed.
+ The <a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/Status">HTTP status code</a> of 200 means "OK", request succeeded
+ then use some JavaScript to getElementById() from the DOM and change its innerHTML to the response text that comes back from our xhr object