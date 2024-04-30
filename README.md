# JavaScript Concepts for Beginners

Welcome to this guide on JavaScript concepts! In this README, we cover basic to intermediate topics with explanations and examples. The topics covered are:
- [Arrays](#arrays)
- [Functions](#functions)
- [Arrow Functions](#arrow-functions)
- [Closures](#closures)
- [Classes](#classes)

Let's dive in and learn with simple examples!

## Arrays
Arrays are used to store multiple values in a single variable. Each value in an array has an index, starting from 0. Here's an example:

```javascript
// An array of fruits
const fruits = ['Apple', 'Banana', 'Cherry'];

// Accessing an item by index
console.log(fruits[0]); // Output: Apple

// Adding an item to the array
fruits.push('Date');
console.log(fruits); // Output: ['Apple', 'Banana', 'Cherry', 'Date']

// Removing the last item from the array
fruits.pop();
console.log(fruits); // Output: ['Apple', 'Banana', 'Cherry']
```

## Functions
Functions are blocks of code designed to perform a specific task. They can take arguments (inputs) and return a value (output). Here's an example of a simple function that adds two numbers:

```javascript
// A function to add two numbers
function add(a, b) {
  return a + b;
}

// Using the function to add numbers
const result = add(5, 3);
console.log(result); // Output: 8


