## Intro to JavaScript (JS)

### What is JavaScript?
Javascript (js) is a interpreted programming language[that is ran inside a browser ( chrome , opera, safari)
]. It allows you to have complex functions on your web page. 
- interactive maps
- 2d/3d graphics
- displaying timely content updates

There are three major parts we refer to as "JavaScript".
    
    1. The language itself.
    2. The DOM API which is how the language can interact with various parts of the web page while in the broswer. 
    3. The Server API provided by Node.js 

**Note** Java and Javascript are completely different !!

##  Arithmetic Operations 
- Addition = +
- Subtraction = -
- Multiplication = *
- Division = /

Outside of math you can also use these operations other ways.
Using + As a way to join to text strings. This also known as **conceatenation**. 
Example: 


    Const name = 'Bingo';
    name;
    const hello = ' says hello';
    hello;
    const greeting = name + hello;
    greeting;

Some operators have shortcut known as **assignment operators**.
An example woud be if you need to add new text string to an existing one get results:

    let name1 = 'Bingo'
    name1 += ' says hello!' ;

### Comparison Operations

Another set of operations is Comparsion operations which is basically a comparsion between the varible and constant and seeing if it is true.
- '===' is Strict Equality ( is it exactly the same?)
- '!==' is Non-equality (is it not the same)
- '<' less than 
- ' >' greater than

## Ways to code JS
To write the JS codeyou can either Embed or Include. Embed mean to code the JS directly in the html file using < script> code between < /script >. To include mean to put a line in the html file that includes a external JS file.


Inputs and outputs are how to interact with JS running in the browser. 
The most simple is **Alert**.
Alert is a pop-up in the browser with text. Its rarely used by the easier way to show JS. Example

    <script language="javascript">

    alert("Hello World");

    </script>

Another way to code in JS is **document.write** and it looks like this:

    first line
    <script>

    document.write("<h1>Hello World</h1>");

    </script>
    Last line 

Moving along the next way to code in JS is **console.log**.Many web browsers call it "JavaScript Console". It is Not normally visiual in the browser but can print out  warnings and error. Here's a example:

    <script>

    console.log ("Hello world")

    </script>


## JavaScript input W/ Prompt and Confirm

### Prompt

A prompt will show up in a popup window w/ text and a textbox the user can fill in. When the user presses OK the value in the text box will be returned. Example:

    <script>

    var name = prompt("Your name:" "");
    document.write("Hello ", name);

    </script>

Another example:

    <script>

    var name = prompt("Please correct your email address:", "foo@bar.co)
    document.write("Your e-mail address is ", name);

    </script>

### Confirm

Comfirm isnt really a input method but it does ask the user a Yes/No question.
Example:

    <script>

    if (confrim("Shall I print Hello World)) {
        document.write("Hello World) ;
    } Else {
        document.write("OK, I won't print it.)
    }
    
    </script>

In this example We are coding to ask a user if they want to print "Hello World".
The coding 'if' and 'else' means true and false.

## JavaScript Variables

### Variables

Variables are containers for storing data. 

    var x = 5;
    var y = 6;
    var z = x + y;

In this Example the variables are x, y ,z .

    let x = 5;
    let y = 6;
    let z = x + y;

In this example x,y,z get value from let; without let they would be undeclared variables

### When to use JavaScript Var, Let, or Const

1. Javascript Var is used when you code for older browsers.
2. Javascript Const is used when there is a general rule set for variables.
3. Javascript Let is used when the vaule of variables can change.

    const price1 = 5;

    const price2 = 6;

    let total = price1 + price2

const are the prices beacause they wont change but the total can thats why it has let.

### JavaScript Identifiers

All JavaScript **variables** must be **identified** w/ **unique names**

These unique names are called identifers. Identifers can have short nameslike x,v,s or long ones like age , sum,totalVolume. finding names for them must fix within the rules

* Names can contain letters, digits, underscores, and dollar signs.
* Names must begin with a letter.
* Names can also begin with $ and _ (but we will not use it in this tutorial).
* Names are case sensitive (y and Y are different variables).
* Reserved words (like JavaScript keywords) cannot be used as names.

### JavaScript Data Types 

JS variables can hold number and text. The text values are called text strings.
Text

