## Read: 03 - HTML Lists, CSS Boxes, JS Control Flow
## Duckett HTML book
## Chapter 3: “Lists” (pp.62-73)

- <ol> - Ordered Lists: It uses numbers
- <ul> - Unordered Lists: It uses bullets
- <li> - st5ands for list item.
- <dl> - definition lists consists of definitions.
- <dt> - contain the term being defined
- <dd> - contain the definition.
Inside the <dl> element you will see pairs of <dt> and <dd>
Lists can be nested inside one another.

## Chapter 13: “Boxes” (pp.300-329)
To set your own dimensions for a box we use **height** and **width** properties.
- Specification: px,%,em.
Overflowing Content:
**overflow** property tells the browser what to do if the content contained withina box is larger than the box itself. it has 2 values
- *hidden* - simpley hides any extra comntent that sits in the box
- *scroll* - adds scrollbar.
`p.one{
    overflow: hidden;
}`
`p.two{
    overflow: scroll
}`

Every box has 3 properties:
- border
- margin 
- padding                                         

## Chapter 4: “Decisions and Loops”
### SWITCH Statements
It allows you to compare a value against possible outcomes and also provides a default option if none match.

```
switch(level) {
    case 'One':
    title = 'Level 1';
    break;

    case 'Two':
    title = 'Level 2';
    break;

    case 'Three':
    title = 'Level 3';
    break;

    default:
    title = 'Test';
    break;
}
```


[<---Back](README.md)