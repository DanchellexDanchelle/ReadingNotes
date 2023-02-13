# Programming with JavaScript

## Control Flow 

Control Flow is the order that the computer runs the code/program. This is Usually from line to line but to loops and Conditionals change the flow often. For example, if a web page needs a user to fill in a text box and they skip. the loop would take the user **back** to the text box. The code that make this happen is the " If..Else" code and it would look like:

    *if (isEmpty(field)) {
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

2. **Parentheses ()** - is next and has the parameter names separated by commas, .

3. **Code to be Executed**- is last and must but surrounded by curly brackets {}.

