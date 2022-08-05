Java Script Promise,Async and Await

A Promise in NodeJS/javaScript/React is similar to a promise in real life. It is an assurance that something will be done. Promise is used to keep track of whether the asynchronous event has been executed or not.
Example of promise 
![image](https://user-images.githubusercontent.com/98147894/183075927-4912be04-2306-4472-b7fd-0dd90d626a99.png)
![image](https://user-images.githubusercontent.com/98147894/183075966-f9a92a72-5580-43a6-ba04-c2cdc814fa62.png)

Async :It is just a wrapper to restyle code and make promises easier to read and use.
This helps to remove many of the problems with nesting that promises have,To use async-await, we just need to create an async function in which we will await our promise to be completed. If it gets resolved we will get the result otherwise an error will be thrown. 
![image](https://user-images.githubusercontent.com/98147894/183076005-f7822800-bc45-4c88-8d90-e2be930eb629.png)

Await can only be used inside an async function or async callback or async arrow function.
![image](https://user-images.githubusercontent.com/98147894/183076035-27a5d5f7-db98-4cbc-9f4b-be972fa12c36.png)

Using Async/Await makes it easier to read and understand the flow of the program as compared to promise chains.
What async/await solves Async/await offers a much cleaner syntax when it comes to handling async behavior. While promises come with a lot of boilerplate, async functions build an abstraction on top of it.
The resulting code is much cleaner and, thus, easier to debug 
Error handling is much simpler, as it relies on try…catch just like in any other synchronous code, and so on.
