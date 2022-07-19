# JS-Course-Notes
// - single line comment
/* */ - multiline comment
var name - creates a variable
let name - creates a variable (different scope)
const name - creates a constant variable

var name = 11 - number var
var name = "abc" - string var
var name = [a,b,c] - creates an array
var person = {
  "name":"Matthew";
  "age": 27;
  }
  /\ creates an object
person.age / person["age"] - two ways to access properties 

name.length - length of the string
####################################
The global method Number() can convert strings to numbers.

Strings containing numbers (like "3.14") convert to numbers (like 3.14).

Empty strings convert to 0.

Anything else converts to NaN (Not a Number).
Number("3.14")    // returns 3.14
Number(" ")       // returns 0
Number("")        // returns 0
Number("99 88")   // returns NaN
####################################
The global method String() can convert numbers to strings.

It can be used on any type of numbers, literals, variables, or expressions:
Example
String(x)         // returns a string from a number variable x
String(123)       // returns a string from a number literal 123
String(100 + 23)  // returns a string from a number from an expression

The Number method toString() does the same.
Example
x.toString()
(123).toString()
(100 + 23).toString() 
####################################
Array.from(variable) - creates an array from variable


variable.forEach(function(item){
// do smth
});


$$$###//DOM MANIPULATION\\###$$$

document.getElementById("id") - returns an elemnt by id
document.querySelector("#id .class tag etc") - returns the first element of the selector
document.querySelectorAll("selector") - returns a node list of elements of the selector

Array.from(document.querySelectorAll(".class") - creates an array of elements with a class name class

element.textContent - gets the text inside of the html element
element.innerHTML - gets the html text of the element


###NODES

element.parentNode - returns parent node of element
element.parentElement - similar to parent node
element.childNodes - returns every child of element
element.children - returns html tags that are children of element
