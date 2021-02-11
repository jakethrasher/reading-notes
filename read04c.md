#### async programming and callbacks
* by default javascript is synchronous, which means that code cannot create new threads  
* asynchronous means that things can happen indepently of main program slow, which is how computers are by design
* in computers, every program runs for a specific time slot and then it stops its execution to let another program continue its execution but its impossible to notice. we are under the impression that our computer runs programs simultaneously but this is not the case
* in javascript, lines of code are executed in a series one after another

* javacript was born inside the browser and in the beginning its main job was to handle events. 
* when user events occur, callback functions are fired 

#### javascript promises
* promises are alternatives to callbacks in javascript
* commonly defined as a proxy for a value that will eventually become available
* creating a promise with the promise API with the constructor new Promise()
* promises allow you to defer further actions until after a previous action has completed
* The Fetch API provides a JavaScript interface for accessing and manipulating parts of the HTTP pipeline, such as requests and responses. It also provides a global fetch() method that provides an easy, logical way to fetch resources asynchronously across the network.