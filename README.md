# java-script

##syntax
#javascript values
The JavaScript syntax defines two types of values:
Literals (Fixed values)
Variables (Variable values)

#literals
syntax rule for literals are
.Numbers are written with or without decimals:
10.50,1100
.Strings are text, written within double or single quotes:
"hello",'hello'

#keywords(they define the action to be performed)
let and constant keywords are used to create variable
Keyword	        Description
var	            Declares a variable
let            	Declares a block variable
const	          Declares a block constant
if	            Marks a block of statements to be executed on a condition
switch	        Marks a block of statements to be executed in different cases
for	            Marks a block of statements to be executed in a loop
function	      Declares a function
return	        Exits a function
try	            Implements error handling to a block of statements


#variables(store values)
.Using let  (Only use let if you cannot use const)
.Using const (Always use const if the value should not be changed)

#data type
Strings are text written inside quotes
Numbers are written without quotes

Type	         Description
String	       A text of characters enclosed in quotes
Number       	 A number representing a mathematical value
Bigint	       A number representing a large integer
Boolean	       A data type representing true or false
Object	       A collection of key-value pairs of data
Undefined	     A primitive variable with no assigned value
Null	         A primitive value representing object absence
Symbol	       A unique and primitive identifier

#javascript booleans
Equal to	
Not equal to	
Greater than	
Less than







#comments
.single line comments
Single line comments start with //
.multi line comments
Multi-line comments start with /* and end with */

#let

let can not be redeclared.
With let you can not do this:
let x = "John Doe";
let x = 0;

var can be redeclared.
With var you can do this:                         
var x = "John Doe";                                
var x = 0;                                         

##operators
#arithmetic operators
+	  Addition
-	  Subtraction
*	  Multiplication
**	Exponentiation (ES2016)
/	  Division
%	  Modulus (Remainder)
++	Increment
--	Decrement

#assignment operator
=	     x = y	  x = y	
+=	   x += y	  x = x + y	
-=	   x -= y	  x = x - y	
*=	   x *= y 	x = x * y	
**=	   x **= y	x = x ** y	
/=	   x /= y	  x = x / y	
%=	   x %= y	  x = x % y	  
:	     x: 45	  size.x = 45

&&=	   true &&= 10	  x = 10
||=	   false ||= 10	  x = 10
??=	    null ??= 10 	x = 10

#comparison operator
=        equal to 
===      equal value and equal type
!=       not equal to 
!==      not equal value or not equal type
>         greater than
<        less than
>=       greater than or equal to
<=       less than or equal to

#conditional operator
Conditional statements include:

if
if...else
if...else if...else
switch
ternary (? :)


#if statement
syntax 
if (condition) {
  // code to execute if true condition exists
}

#else statement 
if (condition) {
  // code to execute if condition is true
} else {
  // code to execute if condition is false
}

#else if statement
if (condition1) {
  // code to execute if condition1 is true
} else if (condition2) {
  // code to execute if the condition1 is false and condition2 is true
} else {
  // code to execute if the condition1 is false and condition2 is false
}

#switch statements
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}


#ternary operator 
condition ? expression1 : expression2

#for loop
The for statement creates a loop with 3 optional expressions:

for (exp 1; exp 2; exp 3) {
  // code block 
}
exp 1 is used to initialize the variable(s) used in the loop 
exp 2 is used to evaluate the condition of the initial variable (i<len)
exp 3 increments the value of the initial variable (i++)

.using variable in loops
var i = 5;
for (var i = 0; i < 10; i++) {
  // some code
}
// Here i is 10

.using let in loops
let i = 5;
for (let i = 0; i < 10; i++) {
  // some code
}
// Here i is 5

#while loop
While loops execute a block of code as long as a specified condition is true.

.The while loop
The while loop loops through a block of code when specified condition is true.
while (condition) {
  // code block to be executed
}

#break statement
The break statement terminates the execution of a loop or a switch statement.

#continue statement
The continue statement skips the current iteration in the loop

#jump statement
break - exits a loop or switch
continue - skips the current loop iteration
return - exits from a function
throw - jumps to error handling

##strings
Strings are for storing text
Strings are written with quotes
ex    let text = "John Doe";
      let answer = 'He is called "Johnny"';

.string also escape character
Because strings must be written within quotes, JavaScript will misunderstand this string:
ex
let text = "We are the so-called "Vikings" from the north.";
The string will print only "We are the so-called ".
To solve this problem, you can use an backslash escape character.
Code	        Result	        Description
\'	            '           	Single quote
\"	            "            	Double quote
\\	            \	             Backslash
ex
\' inserts a single quote in a string:
let text= 'It\'s alright.';

##template strings 

#back tics string
Template Strings use back-ticks (``) rather than the quotes ("") to define a string:
ex
let text = `Hello World!`;

#quotes inside string
Template Strings allow both single and double quotes inside a string:
ex
let text = `He's often called "Johnny"`;

#multiline string
ex
let text =
`The quick
brown fox
jumps over
the lazy dog`;

#interpolation(Interpolation means inserting variables or expressions directly inside a string)

Template Strings allow variables in strings.
Template strings provide an easy way to interpolate variables in strings.
ex
let firstName = "John";
let lastName = "Doe";
let text = `Welcome ${firstName}, ${lastName}!`;

##java script string length
The length property returns the length of a string:
ex
let text = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
let length = text.length;
it gives 26

#Extracting String Characters (Extracting string characters means taking out a letter or character from a string.)
There are 4 methods for extracting string characters:

The at(position) Method
The charAt(position) Method
The charCodeAt(position) Method
Using property access [] like in arrays

.The at(position) Method
The at() method returns the character at a specified position (index) in a string. (support only for positive index)
ex
let str = "JavaScript";
console.log(str.at(0));
output - J 

.The charAt(position) Method
The charAt() method returns the character at a specified index (position) in a string:(support for positive and negative index)
ex
let text = "HELLO WORLD";
let char = text.charAt(0);
output - H

.The charCodeAt(position) Method
The charCodeAt() method returns the code of the character at a specified index in a string:








