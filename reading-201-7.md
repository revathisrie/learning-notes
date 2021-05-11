## Read: 07 - HTML Tables; JS Constructor Functions

## Readings : Object-Oriented Programming, HTML Tables

Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

Here's some tips to follow when building your own domain models.

* When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
* Model its attributes with a constructor function that defines and initializes properties.
* Model its behaviors with small methods that focus on doing one job well.
* Create instances using the `new` keyword followed by a call to a constructor function.
* Store the newly created object in a variable so you can access its properties and methods from **outside**.
* Use the this variable within methods so you can access the object's properties and methods from **inside**.

### Duckett HTML: Chapter 6: “Tables” (pp.126-145)
A table represents information in grid format.
* `<table>`: used to create a table.
* `<tr>`: start of each row.
* `<td>`: table data.
* `<th>`: heading for column or a row.
* `<thead>`: headings of the table should be inside `<thead>` element.
* `<tbody>`: the body should sit inside `<tbody>` element.
* `<tfoot>`: the footer should sit inside `<tfoot>` element.
```
<table>
 <thead>
  <tr>
   <th>Date</th>
   <th>Income</th>
  </tr>
 </thead>
 <tbody>
   <tr>
    <th>1st Jan</th>
    <td>250</td>
   </tr>
   <tr>
    <th>2nd Jan</th>
    <td>260</td>
   </tr>
   </tbody>
   <tfoot>
   <tr>
   <td></td>
    <td>510</td>
   </tr>
  </tfoot>
 </table>
 ```  

### Duckett JS: Chapter 3: “Functions, Methods, and Objects” (pp.106-144)
In an object, varaiables are known as properties of the object; functions are known as methods of the object.

#### Creating Objects using Literal Notation;
```
var hotel = {
    name: 'Rev'
    rooms: 20,
    booked: 25,
    checkAvailability: function(){
        return this.rooms - this.booked
    }
} 
```
#### Creating Objects using Constructor Notation:
```
var hotel = new Object();
    hotel.name: 'Rev'
    hotel.rooms: 20,
    hotel.booked: 25,
    checkAvailability: function(){
        return this.rooms - this.booked
    }
```
* Constructor Notation:
`var hotel = new Object();`

* Updating an Object: dot notation (or) square brackets.
  * `hotel.name = 'Park;`
  * `hotel['name'] = 'Park';`

#### Creating Multiple Objects: Constructor Notation
```
function Hotel(name, rooms, booked){
    this.name: name;
    this.rooms: rooms;
    this.booked: booked;
    checkAvailability: function(){
        return this.rooms - this.booked
    };
}
```
* Creating instances
`var quayHotel = new Hotel('Quay', 40, 25);`
`var parkHotel = new Hotel('Park', 40, 25);`


[<---Back](README.md)