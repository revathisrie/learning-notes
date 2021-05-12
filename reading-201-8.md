## Duckett HTML book:

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
  * `float:left;`
  * `width: 620px;`
  * `margin: 10px;`
* **Grids** help create a professional and flexible designs.


[<---Back](README.md)