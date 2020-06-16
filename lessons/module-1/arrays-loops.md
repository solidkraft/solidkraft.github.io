---
title: Arrays
length: 60
tags: javascript, foundation, arrays
---

## Learning Goals

In this lesson we'll cover:

* Array literals  
* Adding/changing values to arrays via their indices  

## Vocabulary

- `Literal`  A way of declaring a data structure and its values at the same time
- `Array` Used to store a collection of data items/multiple values under a single variable name
- `Element` A single item stored in an array. An element can be of any data type.
- `Bracket Notation` How we access individual elements of an array. Either to
  express the element, or assign a new element.

## Arrays

An array is a complex data type. Instead of storing just one value, it stores an ordered list of values. Each value is referred to as an `element`. You should consider using an array whenever you are working with a collection of values, or values that are related to one another.

You can put different types of data into an array, and there is not a certain number of elements an array can or should contain:

```js
var arrayName = [element0];
var rainbowColors = ['Red', 'Orange', 'Yellow'];
var lotteryNumbers = [33, 72, 64, 18, 17, 85];
```
You can create an array just like you would any other variable, using the `var` keyword followed by the name of your array. The values are assigned to the array inside a pair of square brackets (`[]`), and each element is comma-separated. The above technique for creating an array is known as an **array literal**. You can also write an array with values on separate lines, like so:

```javascript
var colors = [
  'white',
  'black',
  'pink'
];
```

## Accessing Values in Arrays

Each value in an array is automatically given a number called an index. This index can be used to access a particular value in any given array.

Indices begin at 0 and order incrementally. So in the above `colors` example, the following is true:

- color white has an index of 0
- color black has an index of 1
- color pink has an index of 2

You can change values in an array by using their index. Let's walk through it in the console:

```javascript
// Create the array
var colors = ['white', 'black', 'pink'];

// Check the value of colors
colors;

// Update the third value in the array
colors[2] = 'blue';

// Check the value of colors
colors;

// Get the value of the 1st element
colors[0];
```

<section class="call-to-action">
### Your Turn

In the console:  
- create an array of cars
- change the values within the array
- add a new car to the array
- identify the value of the 3rd element of the array
</section>

## Getting Multiple Values from Functions

We learned last week that a single function can only return a single value. There will be times when you want to send a list of values over. We are able to do this by returning an array. Because an array is a complex data type, it has the ability to "wrap up" many values into one value, it doesn't break the rule of "a single function can only return a single value".

```javascript
function combineNames(name1, name2, name3) {
  var names = [name1, name2, name3];
  return names;
}

var listOfNames = combineNames("Luna", "Bey", "Sunny");

listOfNames;
// => ["Luna", "Bey", "Sunny"]

```

### Dig Deeper

* [JS Style Guide](https://github.com/solidkraft/javascript/tree/master/es5)
* [Seven JS Quirks I Wish I'd Known About](http://developer.telerik.com/featured/seven-javascript-quirks-i-wish-id-known-about/#expdec)  
* [Adequately Good JS](http://www.adequatelygood.com/JavaScript-Scoping-and-Hoisting.html)  
