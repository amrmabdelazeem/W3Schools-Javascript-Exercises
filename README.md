# JavaScript tutorial

W3Schools-Javascript-Exercises
We have gathered a variety of JavaScript exercises (with answers) for each JavaScript Chapter.  Try to solve an exercise by editing some code, or show the answer to see what you've done wrong.

# JS Variables

In JavaScript, we can declare varible using three different keywords:
* var : create a variable globally availale throught the program
* let : create a variable available just the block of code declared, as if statement or function
* const : create a read-only reference to a value. 

Create a variabole called carName and assign the value Volvo to it.
```
var carName = "Volvo";
```
Create a variable called X, assign the value 50 to it:
```
var x  = 50;
```
Display the sum of 5+10, using the varuable: x and y
```
var x = 5;
var y = 10;
document.gtElementById("demo").innerHTML = x + y;
```
Create a varialbe called Z, assign x+y to it, and display the result in an alert box
```
var x  = 5;
var y = 10;
var z = x + y;
alert(z);
```
On one sigle line, declare threee variable with the following names and values:
* firstName = "John"
* lastName = "Doe"
* age = 35
```
var firstName = "John" ,  lastName = "Doe" , age = 35;
```

# JS Operators

* ```typeof(x)``` : returns the Datatype of the parameter x
* ```new```       : Keyword that allows to create an instance of an Object or builtin Datatype (ex: String)

## typeof
```
// Will print out : Number
Console.log(typeof(45));

// Will print out : Boolean
Console.log(typeof(true));
```
 ## new
```
function person(name , surname, age)
{
  this.name = name;
  this.surname = surname;
  this.age = age; 
}

const person1 = new person('Davide' , 'Pollicino' , 20);
// Output: 20
console.log(person1.age);
```


Multiply 10 with 5, and alert the result:
```
alert(10*5);
```
Divide 10 by 2, and alert the result:
```
alert(10/2);
```
Alert the remainder when 15 is divided by 9:
```
alert(15%9);
```
Use the assignment operator that will result in x being 15 (same as x = x + y )
```
x = 10;
y = 5;
x += y;
```
Use the correct assignment operator that will result in X being 50 (same as X = X * Y);
```
x = 10;
y = 5;
x *= y;
```

# JS Data types and Arrays

```
// Number
var length = 16; 

// String
var lastName = "Johnson"; 

// Object
var x = {
  firstName: "John",
  lastName: "Doe"
};  

// Array with for elements
var myArray = [1,2,3,4];

// Declare an empty array that will contains for 4 elements
var myArray = new Array(4);
```
# JS Functions
Execyte the function names myFunction

```
function myFunctin()  {
  alert("Hello World!");
}
myFunctin();
```

Create a function called "myFunction()"
```
function myFunction{
  alert("Hello World");
}
```

Make the function return "Hello"
```
function mmyFunction() {
  return "Hello";
}
document.getElementById("demo").innerHTML = myFunctin();
```
Make the function display "Hello" in the inner HTML of the element with the ID "demo"
```
function myFunction() {
  document.getElementById("demo").innerHTML = "Hello";
}
```

# Call js function from a JS file
```
<html>
    <head>
        <script rel="text/javascript" src="ExampleFile.js"> </script>
    </head>
    <body>
    </body>
</html>
```

# JS Object

Alert "John" by extracting information from the person Object
```
var person =  {
  firstName : "John",
  lastName : "Doe"
};
alert(person.firstName);
```

Add the following property and value to the person object: country: Norway.
```
var person = {
  firstName: "John",
  lastName: "Doe",
  country : "Norway"
};
```

Create an object called person with name = John, age = 50. Then, access the object to alert("John is 50")
```
var person = {
  name : "John" , age : 50
};
alert(person.name + " is " + person.age);
```
# JS String
Use the length property to alert the length of txt.

```
var txt = "Hello World!";
var x = txt.length;
alert(x);
```
Use escape characters to alert We are "Vikings".
```
var txt = " ";
We are \"Vikings\"";
alert(txt);
```

Conceteate the two string to alert "Hello World"!
```
var str1 = "Hello ";
var str2 = "World";
alert(str1 + str2);
```
