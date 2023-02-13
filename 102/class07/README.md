# Programming with JavaScript

## Control Flow 

Control Flow is the order that the computer runs the code/program. This is Usually from line to line but to loops and Conditionals change the flow often. For example, if a web page needs a user to fill in a text box and they skip. the loop would take the user **back** to the text box. The code that make this happen is the " If..Else" code and it would look like:

    if (isEmpty(field)) {
  promptUser();
} else {
  submitForm();
}

With loops and conditions like the one above may only be a few lines of code but they can make the control flow very complex by changing the order. So when you read a scriptyou can't just read start to finish but take in a count of the loops and conditions that affect the order.

# JavaScript Functions 

Javascript function is a block of code made to do a task. These function only "function" or work when *something* call to it. 
Example :
    *// Function to compute the product of p1 and p2
function myFunction(p1, p2) {
  return p1 * p2;
}

## JavaScript Function Syntax 

Function syntax must look a certin way. Example:
* function name( Parameter1, parameter2, parameter3) {
    // Code to be executed
}
 
1. **Function names** - this goes first and can contain digits letters, underscores, and dollar signs.

2. **Parentheses ()** - is next and has the parameter names are listed inside and separated by commas, . 

3. **Code to be Executed**- is last and must but surrounded by curly brackets {}.


Function **arugements**(/parameters) are the values of the fuction when it is called.


## Function Invocation 

The code will work when "something" call the function.
* When a event occurs ( when the user clicks a button)
* When its called from the Javascript code
* Automatically ( self Invoked Like a alert)

## Function Return 

Return statements stop the running function.
If the function is invoked from a statement, Javascript will return to run the code after the invoking code.
Functions often compute a **return value**. 

Example: 

* let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}

The result in X will be : 12

## Why Functions ?

So coders use function because you can resuse the code By defining the code once and using it many times. Using different arugments to differ the results. The next example shows this:

* function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius(77);

## The () Operator Invokes the Function

With the example above , *toCelsius* refer to the function object, and *toCelsius()* refers to the function results.
Accessing a function w/o () will return the function object not a function result.

 *function toCelsius(fahrenheit) {
      return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius;

## Functions Used as Variable Values 

Functions can be use the same as variables with Formulas, assignments, and Calculations.

Example
Instead of using a variable to store the return value of a function:

let x = toCelsius(77);
let text = "The temperature is " + x + " Celsius";
You can use the function directly, as a variable value:

let text = "The temperature is " + toCelsius(77) + " Celsius";

## Local Variables 

Variables declared within a Javascript function, and become **local**. Local Variables can only be accessed from Within the function. 

Example
// code here can NOT use carName

function myFunction() {
  let carName = "Volvo";
  // **code here CAN use carName**
}

// code here can NOT use carName

With this information Functions with the same name as a local function can be used in diiferent functions. Local functions are created and deleted at the start and end of the function. 

## Javascript Operators

To assign a value to a variable use a (=) .

Example:

// Assign the value 5 to x
let x = 5;
// Assign the value 2 to y
let y = 2;
// Assign the value x + y to z:
let z = x + y;

For Addition use (+).

Example:

let x = 5;
let y = 2;
let z = x + y;

For Multiplication use (*).

Example: 

let x = 5;
let y = 2;
let z = x * y;


## Types of Javascript Operators 

There are different types of Javascript Operators:

* Arithmetic Operators
* Assignment Operators
* Comparison Operators
* Logical Operators
* Conditional Operators
* Type Operators

## Arithmetic Operators

Arithmetic operators are used to do math on numbers

Operator	Description
(+)	Addition

(-)	Subtraction

(*)	Multiplication

(**)	Exponentiation (ES2016)

(/)	Division

(%)	Modulus (Division Remainder)

(++)	Increment

(--)	Decrement

## Addition Assignment Operator 

Addition assignment Operator (+=) adds a vaule to a variable. 

<table class="ws-table-all notranslate">
<tr>
<th style="width:25%">Operator</th>
<th>Example</th>
<th>Same As</th>
</tr>
<tr>
<td>=</td>
<td>x = y</td>
<td>x = y</td>
</tr>
<tr>
<td>+=</td>
<td>x += y</td>
<td>x = x + y</td>
</tr>
<tr>
<td>-=</td>
<td>x -= y</td>
<td>x = x - y</td>
</tr>
<tr>
<td>*=</td>
<td>x *= y</td>
<td>x = x * y</td>
</tr>
<tr>
<td>/=</td>
<td>x /= y</td>
<td>x = x / y</td>
</tr>
  <tr>
<td>%=</td>
<td>x %= y</td>
<td>x = x % y</td>
  </tr>
<tr>
<td>**=</td>
<td>x **= y</td>
<td>x = x ** y</td>
</tr>
</table>

## Adding JavaScript Strings 

The + can also be use to add Strings together. Also known as concatenate strings 
Example: 
    Let text1 = "john"
    Let text2 = "doe"
    Let text3 = text1 + "" + text2;

results = john doe 

Adding number will give you a sum but adding a number and a string will give you a string. 
Examples:
    Let x = 5 + 5; (answer 10)
    Let y = "5" + 5; (answer 55)
    Let z = "hello" + 5; (answer hello5)

## JavaSCript Comparison Operators 

* == equal to 
* === Equal value or not equal type 
* != Not Equal
* !== Not equal value or not equal type 
* <  Less than 
* (>) Greater than
* (> =) greater than or equal to 
* <= Less than or equal to 
* ? Ternary Operator 

## JavaScript Logical Operators

* && Logical and
* || Logical or 
* ! Logical not 

## Javascript Type Operators

* Typeof - Returns the type of a variable 
* Instanceof - Returns true if an object is an instance of an object type 

## JavaScript Bitwise operators



<div class="w3-responsive">
<table class="ws-table-all notranslate">
<tr>
<th style="width:12%">Operator</th>
<th style="width:25%">Description</th>
<th>Example</th>
<th>Same as</th>
<th>Result</th>
<th style="width:15%">Decimal</th>
</tr>
<tr>
<td>&amp;</td>
<td>AND</td>
<td>5 &amp; 1</td>
<td>0101 &amp; 0001</td>
<td>0001</td>
<td>&nbsp;1</td>
</tr>
<tr>
<td>|</td>
<td>OR</td>
<td>5 | 1</td>
<td>0101 | 0001</td>
<td>0101</td>
<td>&nbsp;5</td>
</tr>
<tr>
<td>~</td>
<td>NOT</td>
<td>~ 5</td>
<td>&nbsp;~0101</td>
<td>1010</td>
<td>&nbsp;10</td>
</tr>
<tr>
<td>^</td>
<td>XOR</td>
<td>5 ^ 1</td>
<td>0101 ^ 0001</td>
<td>0100</td>
<td>&nbsp;4</td>
</tr>
<tr>
<td>&lt;&lt;</td>
<td>left shift</td>
<td>5 &lt;&lt; 1</td>
<td>0101 &lt;&lt; 1</td>
<td>1010</td>
<td>&nbsp;10</td>
</tr>
<tr>
<td>&gt;&gt;</td>
<td>right shift</td>
<td>5 &gt;&gt; 1</td>
<td>0101 &gt;&gt; 1</td>
<td>0010</td>
<td>&nbsp; 2</td>
</tr>
<tr>
<td>&gt;&gt;&gt;</td>
<td>unsigned right shift</td>
<td>5 &gt;&gt;&gt; 1</td>
<td>0101 &gt;&gt;&gt; 1</td>
<td>0010</td>
<td>&nbsp; 2</td>
</tr>
</table>
</div>