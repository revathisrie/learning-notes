## Duckett HTML
## Chapter 2: “Text”(pp.40-61)

- `<h1>` - has 1-6 level of headings
- `<p>` - to create paragraph
- `<b>` - characters appear bold
- `<i>` - characters appear italic
- `<sup>` - used to contain characters that should be superscript
- `<sub>` - used to contain characters that should be subscript
- `<br />` - creates a break
- `<hr />` - creates break between themjes and can add a horizontal rule between sections.

**Semantic Markup** are some elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages

- `<strong>` - displays in bold.
- `<em>` - displays in italic
- `<blockquote>`  - It is used for longer quotes
- `<q>` - used for shorter quotes
- `<abbr>` - used to define abbreviation.
- `<cite>` - used to indicate where citation is from and text becomes italic
- `<dfn>` - defining instance of a new term. Some browsers show these elements in italics
- `<address>` - contain contact details or email addess. ome browsers show these elements in italics
- `<ins>` and `<del>` - show content that has been inserted into a document and deleted from a document and usually has a line through it
- `<s>` - no longer accurate and displayed with a line through center.


## Chapter 10: Ch.10 “Introducing CSS” (pp.226-245)

CSS treats each HTML element as it appears inside its own box and uses rules to indicate how that element should look.

 CSS associates Style Rules with HTML elements:
 It contains 2 parts:
 * Selector
 * Declaration
p{
    font-family:Arial;
}
   * p - selector
   * font-family:Arial - Declaration

CSS declaration inside curly brackets made of 2 parts:
* Property
* Value
h1, h2, h3{
    font family: Arial;
    color: yellow
}
  * color - property
  * value - yellow
This rule indicates all `<h1>,<h2>,<h3>` elements should be shown in the Arial typeface in a yellow color. 

### External CSS:
 * `<link>`
 * href
 * type
 * rel
     * Ex: `<link href="css/styles.css" type="text/css"
       rel="stylesheet"/>`
### Internal CSS
  * `<style>`
      * Ex: `<style type="text/css">`
It usually sits inside `<head>` element of the page.

### CSS Selectors:
* Universal Selector: `* {}` targets all elements on the page
* Type Selector: `h1, h2, h3, {}` targets `<h1>, <h2>, <h3>` elements.
* Class Selector: `.note {}` targets any element whose id attribute has a value of note. 
* ID selector: `#introduction {}` targets the element whose id attribute has a value of introduction.
* Child Selector: `li>a {}` targets any `<a>` element that are children of `<li>` element. 
* Descendant Selector: `li a {}` targets any `<a>` element that sits inside of `<li>` element. . 
* Adjacent Sibling Selector: `h2 + p {}` targets the first `<p>` element after any `<h1>` . 
* General Sibling Selector: `h2~p {}` If you had two `<p>` elements that are siblings of an `<h1>` element this rule would apply to both.

### Cascade Rules:
* LAST RULE: If the two selectors are identical, the second will take precedence.
* If one selector is more specific than the others, the specific rule will take precedence.
* `!important`after any property value indicates that it is more priority.

## Chapter 2: “Basic JavaScript Instructions” (pp.53-84)
### Variables:
   * var
   * let
   * const

### Including Comments
Comments are important because they help other people understand what is going on in your code or remind you if you forgot something yourself. Keep in mind that they have to be marked properly so the browser won’t try to execute them.

* Single-line comments — To include a comment that is limited to a single line, precede it with //
* Multi-line comments — In case you want to write longer comments between several lines, wrap it in /* and */ to avoid it from being executed

### Data Types:
Variables can contain different types of values and data types. You use = to assign them:

* Numbers — var age = 23
* Variables — var x
* Text (strings) — var a = "init"
* Operations — var b = 1 + 2 + 3
* True or false statements — var c = true
* Constant numbers — const PI = 3.14
* Objects — var name = {firstName:"Revathi", lastName:"Mylavarapu"}

### Objects
Objects are certain kinds of variables. They are variables that can have their own values and methods. The latter are actions that you can perform on objects.
  * Ex: var person = {
            firstName:"Revathi",
            lastName:"Mylavarapu",
            age:26,
            place:"Bellevue"
          };

### Arrays
Arrays are special types of variables that store more than one piece of related information.
 -  Each item in an array is automatically given a number called an index.

## Chapter 4: “Decisions and Loops” (pp.145-162)

### Logical Operators:
- Logical AND - &&
- Logical OR - ||
- Logical NOT - !

### IF Statements:
The if statement evaluates a condition. If the condition is true, statements in the code are executed.

### IF else:
if statement checks a condition. if ites true the first code block is executed. If it is false, the second code block is executed.

### SWITCH Statements:
It starts with a variable called *switch value*. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.
- You have a default option that is run if none of the cases match.

### The seven rules of a great Git commit message
- Separate subject from body with a blank line
- Limit the subject line to 50 characters
- Capitalize the subject line
- Do not end the subject line with a period
- Use the imperative mood in the subject line
- Wrap the body at 72 characters
- Use the body to explain what and why vs. how



[<---Back](README.md)