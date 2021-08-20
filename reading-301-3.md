## Readings: Passing Functions as Props

## Lists and Keys
This document is available [here](https://reactjs.org/docs/lists-and-keys.html)

Reference on map() function.[link](https://www.pluralsight.com/guides/how-to-use-the-map()-function-to-export-javascript-in-react)

### Map() Function
The map() function is used to iterate over an array and manipulate or change data items. In React, the map() function is most commonly used for rendering a list of data to the DOM.

### Keys
A “key” is a special string attribute you need to include when creating lists of elements in React. Keys are used to React to identify which items in the list are changed, updated, or deleted. In other words, we can say that keys are used to give an identity to the elements in the lists.

## Using the Spread Operator
This document is available [here](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

The spread operator (`...`) is used to manipulate arrays. It includes
- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments
- Adding an item to a list
- Adding to state in React
- Combining objects
- Converting NodeList to an array

#### Concatenating arrays:
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩

## Video: How to Pass Functions Between Components
This Video is available [here](https://www.youtube.com/watch?v=c05OL7XbwXU)

[React Tutorial through ‘Declaring a Winner’](https://reactjs.org/tutorial/tutorial.html)
[React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)


[<---Back](README.md)
