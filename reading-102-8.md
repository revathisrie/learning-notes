# Read: 08 - Operators and Loops

## Duckett: JavaScript & jQuery:
## Comparison and logical operators: 150-151, 156, and 157

* **Comparison operators** — operators that compare values and return true or false. 
The operators include: `>, <, >=, <=, ===, and !==`.
* **Logical operators** — operators that combine multiple boolean expressions or values 
and provide a single boolean output. The operators include: &&, ||, and !.

## While Loop
* The loop consists of the keyword while followed by an expression and curly braces. The contents of the loop what is between the curly braces are executed as long as the expression evaluates to true.
* while(count < 10) {
  *  console.log(count);
 }

Now, the example above is incomplete because a while loop needs a way to eventually exit the loop. Normally, this is done by modifying the variable in the expression.
* Ex:  let count = 1;
     * while(count < 10) {
     * console.log(count);
     * count++;
}

## For Loop
A for loop is more structured than the while loop. The keyword for is used, followed by three statements:
* initialization: executed before the loop begins
* expression: evaluated before each iteration, exits the loop when false
* increment: executed at the end of each iteration
* Ex:  for(count=1; count < 10; count++) {
    * console.log(count);
    * }

## When to Use Each Loop
while loops when I do not know the number of iterations ahead of time and for loops when I do know.
* Use a for loop to iterate over an array.
* Use a for loop when you know the loop should execute n times.
* Use a while loop for reading a file into a variable.
* Use a while loop when asking for user input.
* Use a while loop when the increment value is nonstandard.



[<---Back](README.md)