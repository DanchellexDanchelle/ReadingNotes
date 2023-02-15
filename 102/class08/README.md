
## Assignment Operators

Assignment operators gives a value to the left based on the right. A Simple Assignment operator is =. An example using that would be x=f(). This means that x is assigned the value of f().

## Comparison Operators

A comparsion operator compares two operands and returns a logical value based on if the comparsion is true. The operands can be numbers, strings, logical, or  object values. The operands dont have to be the same. If they arent the same JavaScript will convert them to compare them (usually using number). 
Example : 
    const var1 = 3;
    const var2 = 4;


## Loops and Iteration

## For Statement
A for loop repeats until a condition is evaluates to be false.
A for statement looks like :
    for (initalization; condition; afterthought)
    statement

When the for loop is running a few things happen:

1. The initializing expression is executed. Starts one or more loop counters but the syntax allows an expression of any degree of complexity.

2. The condition is evaluated. If the conidition is true the loop statment executes, if not the loop ends.

3. The statement executes/runs. To run more than one statement , use a block statement {} to group them together. 

4. If present, the update expression afterthought is executed.

5. restart at Step 2

## While Statement

While statement runs its statement as long as the condition is true. While statement looks like:
    while (condition) 
        statement

If the condition becomes false, the statement in the loops stops running and the control passes to the statement following the loop.
The conidition test happens before statement in the loop is executed. If the condition returns true, Statement is runs and condition is tested again. If the condition returns false, the execution stops and the control is passed to the statement. To execute multiple statement use a block statement { }.

    let n = 0 
    let x = 0 
    while (n < 3) {
        n++;
        x += n;
    }

## Things I want to Know more About 

In the reading it said JS and C++ had a similar element is this true for many things in other code lanauges. 
