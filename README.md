# Basic Javascript (loops, conditionals, strings, arrays & functions)

Welcome to the Basic Javascript Readme! In this guide, you'll find a brief overview of fundamental concepts in Javascript, including loops, conditionals, strings, arrays, and functions. This is a great starting point for anyone looking to learn the basics of Javascript programming.

## Table of Contents

1. [Loops](#loops)
2. [Conditionals](#conditionals)
3. [Strings](#strings)
4. [Arrays](#arrays)
5. [Functions](#functions)
6. [Short Example](#short-example)

## Loops

Loops are essential for repeating a set of instructions multiple times. In Javascript, we have different types of loops, such as `for`, `while`, and `do...while`. Here's a simple `for` loop example:

```javascript
for (let i = 0; i < 5; i++) {
  console.log("Iteration:", i);
}
```

## Conditionals

Conditionals allow us to make decisions in our code based on certain conditions. The most common conditional statement is the if statement. Here's an example:

```javascript
const age = 20;

if (age >= 18) {
  console.log("You are an adult.");
} else {
  console.log("You are a minor.");
}
```

## Strings

Strings are used to represent text in Javascript. We can manipulate strings in various ways. Here's a basic string example:

```javascript
const message = "Hello, world!";
console.log(message);
```

## Arrays

Arrays are used to store multiple values in a single variable. They are incredibly useful for working with collections of data. Here's a simple array example:

```javascript
const numbers = [1, 2, 3, 4, 5];
console.log(numbers);
```

## Functions

Functions are reusable blocks of code that perform specific tasks. They help in organizing and modularizing code. Here's a basic function example:

```javascript
function greet(name) {
  return "Hello, " + name + "!";
}

console.log(greet("John"));
```

## Short Example

Now let's put it all together in a short example that uses loops, conditionals, strings, arrays, and functions:

```javascript
function printEvenNumbers(limit) {
  const evenNumbers = [];

  for (let i = 1; i <= limit; i++) {
    if (i % 2 === 0) {
      evenNumbers.push(i);
    }
  }

  return evenNumbers.join(", ");
}

const numberLimit = 10;
const evenNumbersList = printEvenNumbers(numberLimit);
console.log("Even numbers up to", numberLimit, ":", evenNumbersList);
```

This example defines a function printEvenNumbers that takes a limit as input and returns a string of even numbers up to that limit. It then uses a loop and conditional to find the even numbers and stores them in an array. Finally, it returns a formatted string of the even numbers.

\
Feel free to explore the codebase and learn alongside me as I continue to refine my JavaScript skills.

If you have any suggestions, feedback, or questions, please feel free to reach out. Happy coding! 🚀
