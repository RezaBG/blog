Title: JavaScript Fundamentals - A Beginner's Guide
Date: 2024-10-14 23:35
Category: Programming

# JavaScript Fundamentals - A Beginner's Guide

As I embark on my journey to learn JavaScript, here are a few basic concepts that I've learned so far, including objects, and data types.

### 1. Objects: The Basics

In JavaScript, **objects** are a fundamental building block of the language. They allow you to store collections of data and more complex entities. An object is essentially a collection of key-value pairs.

#### Example:

```javascript
const person = {
  name: "Reza",
  age: 28,
  profession: "Developer"
};
```

In this example, the object `person` contains three properties: `name`, `age`, and `profession`.

- **Accessing Object Properties**: You can access object properties using either dot notation or bracket notation:

```javascript
console.log(person.name);  // Dot notation
console.log(person["age"]);  // Bracket notation
```

- **Adding Properties**: You can also dynamically add new properties to an object:

```javascript
person.location = "Germany";
```

### 2. Data Types

JavaScript supports a wide variety of **data types**, which are divided into two categories: **primitive types** and **objects**.

#### Primitive Types:

- **String**: Represents text, e.g., `"Hello, World!"`
- **Number**: Represents numeric values, e.g., `42` or `3.14`
- **Boolean**: Represents logical values, `true` or `false`
- **Undefined**: A variable that has been declared but not yet assigned a value
- **Null**: Represents an empty or non-existent value
- **Symbol**: A unique and immutable value used as the key of an object property

#### Example:

```javascript
let message = "Hello, JavaScript!";  // String
let count = 10;                      // Number
let isLearning = true;               // Boolean
let notDefined;                      // Undefined
let nothing = null;                  // Null
```

### Conclusion

These are just a few of the basic building blocks in JavaScript, and understanding them is crucial to working with the language. Objects and data types will be used frequently as I continue my journey through JavaScript.

Stay tuned for more updates as I dive deeper into JavaScript!
