# Duckett: HTML & CSS

## Chapter 10: Introducing CSS:
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
This rule indicates all <h1>,<h2>,<h3> elements should be shown in the Arial typeface in a yellow color. 

## External CSS:
 * <link>
 * href
 * type
 * rel
Ex: <link href="css/styles.css" type="text/css"
       rel="stylesheet"/>
## Internal CSS
  * <style>
Ex: <style type="text/css">
It usually sits inside <head> element of the page.

## CSS Selectors:
* Universal Selector: `* {}` targets all elements on the page
* Type Selector: `h1, h2, h3, {}` targets <h1>, <h2>, <h3> elements.
* Class Selector: `.note {}` targets any element whose id attribute has a value of note. 
* ID selector: `#introduction {}` targets the element whose id attribute has a value of introduction.
* Child Selector: `li>a {}` targets any <a> element that are children of <li> element. 
* Descendant Selector: `li a {}` targets any <a> element that sits inside of <li> element. . 
* Adjacent Sibling Selector: `h2 + p {}` targets the first <p> element after any <h1> . 
* General Sibling Selector: `h2~p {}` If you had two <p> elements that are siblings of an <h1> element this rule would apply to both.

## Cascade Rules:
* LAST RULE: If the two selectors are identical, the second will take precedence.
* If one selector is more specific than the others, the specific rule will take precedence.
* `!important`after any property value indicates that it is more priority.

## Chapter 11: Color
There are 3 ways to specify colors in CSS:
 * RGB values
   * Ex: rgb(100,100,90)
* hex codes
   * Ex: #ee3e80
* color names
   * Ex: DarkCyan


[<---Back](README.md)