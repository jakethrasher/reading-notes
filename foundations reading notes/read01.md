### JS Templates and forEach() method
* Template literals user back-ticks (``) instead of quotes to handle strings. 
* Template literals offer an easier way to manage string interpolation and substitution. 
* String substitutions are expressions inbedded in the string. Expressions can be variables, functions, math operations, method calls etc
 
    ``` 
    let user = {
      Name: Timmy
     }
     console.log(`Hi ${user.name}, how are you?`)

     //Hi Timmy, how are you?

* Another nifty feature of template literals is that the white space inside the back-tick will also be considered part of the string. Which means you can easily create multi-line strings

* The ability to add HTML templates into our code with template literals was new to me. Super cool.

## The forEach() method

* the forEach() method loops over an array and executes the same code for each element of the array.
* forEach() takes an argument of a callback function
* during each execution, the element of the array is passed as an argument in the callback function
* the return value for forEach() will always be `undefined`