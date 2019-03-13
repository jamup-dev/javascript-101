# Syllabus for JavaScript - 101

---

## Part 1 - Concepts and Setup

### Explain concepts

-   What is a language.
-   What is JavaScript and the relation with Java.
-   Why do we need JavaScript.
-   What programmers are supposed to do.
-   How JavaScript is evolving and how we need keep in touch.

### Building blocks of programming

-   Concepts of declaration, expression and statement.
-   Concepts of storing values and reusing.
-   Concepts of creating routines (functions), loops, conditions and branching.

### Setup Learning Environment

-   Preferably use a Unix like OS, e.g, Linux, OSX, WSL or git bash in windows.
-   For those using windows, install a terminal like Hyperjs.
-   Install latest version of Chrome.
-   Introduction to the dev tool and writing the first code.
-   Install Nodejs for a rather fun development environment.
-   Some boilerplate shortcut to be effective when learning. (a preset
    browser-sync dev environment provided by the faculty).

---

## Part 2 - Language Basics

### Declaration, Expression and Statements

-   Declaration initiates a value.
-   Expression produces a value.
-   Statement performs an action.

### Variables and Scope

-   How do we declare variables in JavaScript.
-   What are different types of scopes, lexical, block, global.
-   Why did we need `const` and `let`.
-   Concept of variable reassignment and `const`.

### Primitives

-   Number.
-   String.
-   Boolean.
-   Symbol.
-   Others -> null, undefined.

### Object

-   What is Object.
-   Creating object.
-   Accessing properties of object.
-   Reference variable.
-   Equality of objects.

### Array

-   What is Array.
-   Creating an Array.
-   Accessing items of array.
-   Length of an Array.
-   Reference and Equality of array.
-   Checking if an object is an array.

### Learning statements

-   `if...else` condition.
-   `for` loop.
-   `for...in` loop.
-   `do...while` loop.

---

## Part 3 - Functions

### Basics of functions

-   Function declaration.
-   Function parameters.
-   Named and anonymous function expressions.
-   Arrow function expression.
-   Immediately invoked function expression (iffe).

### Prototypal inheritance in JavaScript

-   Constructor functions.
-   Scope of this.
-   Prototypal inheritance.
-   Scope of `this` for regular functions, when called from an object.
-   Scope of `this` for arrow functions.
-   When to use arrow function.
-   Changing `this` of functions.

### Parameters

-   Variable parameters.
-   Rest parameters.
-   Spread parameters.

### Advance Functional patterns

-   Curry functions.
-   High order functions.
-   Compose functions.

### Classes

-   Explain how it is a syntactic sugar.
-   constructor.
-   class methods.
-   class properties.
-   static methods and properties.
-   Inheritance.
-   Using rest and spread on constructor.

---

## Part 4 - Advanced Language Features

### Revisit objects

-   Shallow copy with `Object.assign`, ES spread operator.
-   Object destructure.
-   with ES rest.
-   `const` and object mutation.
-   Shorthand object property and methods.
-   Scope of `this` in object methods.
-   Looping with `Object.keys` and `Object.entries`.

### Revisit Array

-   Shallow copy with ES spread operator and `array.prototype.slice`.
-   Destructure arrays.
-   With rest.
-   Looping with `forEach` and `for..of`.
-   Iterate with array.entries.
-   array.map, array.reduce, array.filter.
-   array.sort.
-   array.find, array.findIndex,
-   array.includes, array.some and array.every.
-   Array.from and Array.of.

### Template Literals

-   Introduction to template literals.
-   Multi-line strings.
-   Expression interpolation.
-   Nesting templates.
-   Tagged template literals.

### Generator and Iterator

-   Generator functions.
-   Custom generator with `Symbol.Iterator`.
-   `for...of` loop.

### Set and WeakSet

-   Set.
-   WeakSet.
-   Garbage collection with WeakSet.

### Map and WeakMap

-   Map.
-   WeakMap.
-   Garbage collection with WeakMap.

---

## Part 5 - Asynchronous JavaScript

### Promises

-   Concept of promise.
-   Example using browser `fetch`.
-   Creating your own promise.
-   Error handling with promise.
-   Resolving multiple promises with `Promise.all`.
-   Example - Convert classic event listener into promise.

### Async/Await

-   What is `async` function.
-   How we can `await` promises inside `async` functions.
-   Error handling with `async` functions.
-   Resolving multiple promises with `await`.
-   Refactor promise callbacks with async-await.
