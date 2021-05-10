## Read: 06 - JS Object Literals; The DOM
### Chapter 3: “Object Literals” (pp.100-105)

Objects group together a set of variables and functions to create a model of something you would recognise from the real world.
* Ifa variable is part of an object, it is called a **Property**
* If a function is part of an object, it is called **Method**

### Creating an object: Literal Notation:
```
var hotel ={
    name: 'Revathi',
    rooms: 40,
    booked: 25,

    checkAvailability: function(){
        return this.rooms - this.booked;
    }
};
```

### Accessing an Object and DOT Notation
```
var hotelName = hotel.name;
var rommsFree = hotel.checkAvailability();

(or)

var hotelName = hotel['name'];
var rommsFree = hotel['checkAvailability']();
```

## Chapter 5: “Document Object Model” (pp.183-242)

The DOM specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

#### Accessing Elements:
DOM queries may return one element, or they return a NodeList, which is a collection of nodes.

Methods that return a Single Element Node:
* `getElementById('id')`
* `querySelector('CSS selector')`

Methods that return one or more elements(as a nodelist):
* `getElementsByClassName('class')`
* `getElementsByTagName()`
* `querySelectorAll('CSS selector')`

Methods that select individual Elements:
* `document.getElemenById('one')`




 [<---Back](README.md)