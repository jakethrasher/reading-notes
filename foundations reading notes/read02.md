### reading notes
Part 1 and 2 discuss the atomic design model. It basically just teaches you how to break up a web page into its components. It uses the analogy of organisms being made of molecules, which are composed of atoms. It web design, an organism would a component. Like a header for example. Atomic design provides a way to conceptualize how to break interfaces down into building blocks. 

Callback funcrtions are functions that are passed as arguments into other functions. A function that passes a function as an arguemnt is called a higher-order function. The function it passes is the callback. I enjoyed the exercise of creating the doHomewor() function in the reading. Here it is:

```
function doHomework(subject, callback){
    alert(`starting my ${subject} homework`);
    callback()
}
doHomework('math', function(){ alert(
    'finshed my homework'
)})
```
Here we defined the callback function in the function call but it could have be defined elsewhere.

Javascript classes are used to create objects with the constructor method.

```
class People{
    constructor(name, age){
        this._name=name;
        this._age=age;
    }
    get name(){
        return this._name;
    }
    get age(){
        console.log(`They are ${this._age}`);
    }
    activity(line){
        console.log(this._name + ' is studying ' + line);
    }
};

class Person extends People{
    constructor(name,age){
        super(name,age)
    }
};

const wk = new Person('Wesley-kate', 25);
wk.age;
wk.activity('television');

