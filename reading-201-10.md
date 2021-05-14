## Duckett JS
### Ch. 10, “Error Handling & Debugging”

#### Error Objects:
This can help you find where your mistakes are and browsers have tools to help you read them.
* 7 Types of Native Errors in JavaScript You Should Know:
  *  **RangeError**: This is thrown when a number is outside an allowable range of values.
  * **ReferenceError**: This error is thrown when a reference made to a variable/item is broken. That is the variable/item doesn’t exist.
  * **SyntaxError**: This error is caught by the JS engine during parsing. There are different stages in the JS engine our code is put through before we see those results on the terminal.
   * tokenization
   * parsing
   * interpreting
  * tokenization breaks the source of the code into individual units. At this stage, numbers, keywords, literals, operators are sorted out and individually marked.
* Next, the token stream generated will be passed to the parsing stage, which is handled by a parser. This is where an AST is generated from the token stream. AST is an abstract representation of the structure of our code.
* During these two stages, tokenization and parsing, if the syntax/source of our codes doesn’t conform to the syntax rules of JS makes the stages fail and throw SyntaxError.
* **TypeError**: TypeError occurs when an operation is performed on a wrong data type. Maybe a boolean is expected but a sting is found.
* **URIError**: (Uniform Resource Indicator) in JS has the functions: decodeURI, decodeURIComponent, etc.
If we call any of them with the wrong parameter we will get a URIError.
* **EvalError**: used to identify errors when using the global eval() function.
* **InternalError**: This occurs when the JS engine is overwhelmed by too many recursions, too many switch cases, etc.

#### How to look Errors in Chrome:
* The console will show you when there is an error in your JavaScript. It also displays the line where it became a problem for the interpreter.

* You can also just type code into the console and it will show you results.

* **BREAKPOINTS**: You can pause the execution orf a script on any line using breakpoints. Then you can check the values stored in variables at that point in time.

* Handling Exceptions:
If you know your code might fail, use try, catch and finally. Each one is given its own block.

#### Throw error NaN:
If you try to use a string in a mathematical operation(other than addition), you do not get an error, you get a special value called **NaN**(Not a Number)



[<---Back](README.md)