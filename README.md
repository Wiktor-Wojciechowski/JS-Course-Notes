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
