## Read: 04 - HTML Links, CSS Layout, JS Functions
### Chapter 4:Links (pp.74-93)

Links allow you to move from one web page to another. It is created using `<a>` tag.
Ex: `<a href="http://www.imdb.com">IMDB</a>`
* URL stands for Uniform Resource Locator
* Absolute URL 
   * Ex: `<a href="http://www.empireonline.com">Empire</a>`
* Relative URL
   * Ex: `<a href="index.html">Home</a>`

* **mailto**: to create a link that starts up the users email.     
  * Ex: <`a href="mailto:jon@example.org">Email Jon</a>`
* **target**: If you wan5t to open in a new window.
  * Ex: `<a href="http://www.imdb.com" target="_blank">Internet Movie Datbase</a>`

You can use the id attribute to target elemts within a page that can be linked to.

### Chapter 15: “Layout” (pp.358-404)

CSS treats each HTML element as if it is in its own box which can be either **Block-level** box or an **inline** box.
* Block-Level Elements - starts on a new line.
 * Ex: `<h1>,<p>,<ul>,<li>`
* Inline Elements - Flow in between surrounding text.
  * Ex: `<img>,<b>,<i>`

**Controlling the Position of Elemts**
* Normal Flow- `position:static`
* Relative Positiong- `poition:relative` 
* Absolute Positing- `position:absolute`
* Fixed Positing-`position:fixed`
When you use relative,fixed or absolute positioning, boxes can overlap. To fix this we use **z-index**
 Ex: `z-index:10;`

### Float:
The float property was introduced to allow web developers to implement simple layouts involving an image floating inside a column of text, with the text wrapping around the left or right of it.
`float:left;`
`width: 620px;`
`margin: 10px;`
**Grids** help create a professional and flexible designs.

## Chapter 3 (first part): “Functions, Methods, and Objects” (pp.86-99)
### Functions:
* It is a block of code designed to perform a particular task.
* Function parameters are listed inside the parentheses () in the function definition.
* Function arguments are the values received by the function when it is invoked.
* Inside the function, the arguments (the parameters) behave as local variables.

### Why Functions:
* You can reuse code: Define the code once, and use it many times.
* You can use the same code many times with different arguments, to produce different results.

* Declaring a Function.
```
function sayHello()
{
    document.write('Hello') 
}
sayHello(); // Calling a Function
```
* Declaring Functions that need Information
```
function getArea(width, height){
    return width*height
}
```
### Variable Scope:
The location where you declare a variable will affect where it can be used within your code. If you declare it within a function, it can only be used within that function.
* Local Variable - created inside a function
* Global Variable - created outside a function.


[<---Back](README.md)