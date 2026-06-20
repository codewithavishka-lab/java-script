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










