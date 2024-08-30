<div align="center">
	
# [LearnJS](https://github.com/dev-aditya-lab/JavaScript)

</div>

# JavaScript Learning Roadmap
Welcome to the JavaScript Learning Roadmap! This guide will help you master JavaScript, from the basics to advanced concepts. Follow the steps below to enhance your JavaScript skills.

## Table of Contents

1. [Introduction to JavaScript](#introduction-to-javascript)
2. [JavaScript Basics](#javascript-basics)
3. [Control Structures and Loops](#control-structures-and-loops)
4. [Functions and Scope](#functions-and-scope)
5. [Object-Oriented Programming (OOP)](#object-oriented-programming-oop)
6. [Asynchronous JavaScript](#asynchronous-javascript)
7. [JavaScript in the Browser](#javascript-in-the-browser)
8. [Advanced JavaScript Concepts](#advanced-javascript-concepts)
9. [JavaScript Ecosystem and Tools](#javascript-ecosystem-and-tools)
10. [Projects and Practice](#projects-and-practice)

---

## Introduction to JavaScript

- What is JavaScript?
- History and Evolution of JavaScript
- JavaScript in Modern Web Development
- Setting Up Your Development Environment

## JavaScript Basics

- **Variables**: `let`, `const`, and `var`
- **Data Types**: Strings, Numbers, Booleans, Null, Undefined, Objects, Symbols
- **Operators**: Arithmetic, Assignment, Comparison, Logical, Conditional (Ternary)
- **Type Coercion and Conversion**

## Control Structures and Loops

- **Control Structures**: `if`, `else if`, `else`, `switch`
- **Loops**: `for`, `while`, `do...while`
- **Break and Continue**: Controlling Loop Flow

## Functions and Scope

- **Function Declarations and Expressions**
- **Arrow Functions**
- **Parameters and Arguments**
- **Default Parameters**
- **Rest and Spread Operators**
- **Closures**
- **Scopes**: Global, Local, Block

## Object-Oriented Programming (OOP)

- **Objects**: Creation, Properties, and Methods
- **Prototypes and Inheritance**
- **Classes**: Syntax, Constructors, and Inheritance
- **Encapsulation and Modules**

## Asynchronous JavaScript

- **Callbacks**
- **Promises**: Creating, Chaining, and Error Handling
- **Async/Await**: Writing Clean Asynchronous Code
- **Event Loop and Concurrency Model**

## JavaScript in the Browser

- **DOM Manipulation**: Selecting and Modifying Elements
- **Event Handling**: Listening and Responding to Events
- **Web APIs**: Fetch API, Local Storage, and More
- **Understanding Browser Compatibility and Polyfills**

## Advanced JavaScript Concepts

- **Error Handling**: `try`, `catch`, `finally`, and Throwing Errors
- **Regular Expressions**: Patterns and Usage
- **JavaScript Engine and Runtime**: V8, Chakra, SpiderMonkey, etc.
- **Memory Management and Performance Optimization**
- **Security in JavaScript**: XSS, CSRF, and Best Practices

## JavaScript Ecosystem and Tools

- **Package Managers**: npm, Yarn
- **Module Bundlers**: Webpack, Parcel, Rollup
- **Transpilers**: Babel and TypeScript
- **Linters and Formatters**: ESLint, Prettier
- **Testing Frameworks**: Jest, Mocha, Chai
- **Build Tools and Automation**: Gulp, Grunt

## Projects and Practice

- **Beginner Projects**: Calculator, To-Do List, Tic-Tac-Toe
- **Intermediate Projects**: Weather App, Movie Database, Quiz App
- **Advanced Projects**: E-commerce Website, Social Media Dashboard, Real-Time Chat Application
- **Contributing to Open Source Projects**
- **Code Challenges and Online Platforms**: LeetCode, Codewars, HackerRank

---

Feel free to modify and add more details to each section as you progress through your JavaScript journey. Happy coding!

---

### Additional Resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [JavaScript.info](https://javascript.info/)
- [Eloquent JavaScript](https://eloquentjavascript.net/)

---

This roadmap gives a structured pathway to learning JavaScript, starting from the basics and advancing to more complex topics, with plenty of practice and project opportunities along the way.

-------------------------------------------------------------
<div align="center">
	
# [Let's get started](https://github.com/dev-aditya-lab/JavaScript)

</div>

## Variables
- A variable is a container that stores data in RAM.
- Variable names can start with `$`, `_`, or a letter but not a number.
- `Harry` is not equal to `harry`.

### Types of Scopes
1. `let`
2. `var`
3. `const`

- `let`: Initialization is optional.
- `const`: Initialization is required.
- `var`: Initialization is optional.

<div align="center">

|       | Block Scoped | Hoisting | Reassignment | Initialization |
|-------|---------------|----------|--------------|----------------|
| `let` | Yes           | No       | Yes          | Optional       |
| `var` | No            | Yes      | Yes          | Optional       |
| `const`| Yes          | No       | No           | Required       |

</div>

## Primitive Data Types
1. `null`
2. `number`
3. `symbol`
4. `string`
5. `boolean`
6. `bigint`
7. `undefined`

### Examples:
```javascript
let a = null;
let b = 345;
let c = true; // can also be false
let d = BigInt("567") + BigInt("3");
let e = "Harry";
let f = Symbol("I am a symbol");
let g;
```

### Type of a Variable
```javascript
console.log(typeof a); // Output: object
```

## Objects
Objects in JavaScript are similar to dictionaries in Python (key-value pairs).

### Accessing Object Values
1. `objectname.key`
2. `objectname["Keyname"]`

## Operators

### Arithmetic Operators
- `+`, `-`, `*`, `**`, `/`, `%`, `++`, `--`

### Assignment Operators
- `=`, `+=`, `-=`, `/=`, `%=`, `*=`, `**=`

### Comparison Operators
- `==`: Equal to (does not check the type).
- `!=`: Not equal to (does not check the type).
- `===`: Equal value and equal type.
- `!==`: Not equal value and not equal type.
- `>`, `<`, `>=`, `<=`

### Logical Operators
- `&&`: Logical AND
- `||`: Logical OR
- `!`: Logical NOT

## Comments in JavaScript
```javascript
// Single line comment

/* 
   Multi-line comment 
*/
```

## Conditional Statements
1. **if-else**
   ```javascript
   if (condition) {
       // code to be executed if condition is true
   } else {
       // code to be executed if condition is false
   }
   ```

2. **Nested if-else**
   ```javascript
   if (condition1) {
       // code to be executed if condition1 is true
   } else if (condition2) {
       // code to be executed if condition2 is true
   } else {
       // code to be executed if both conditions are false
   }
   ```

3. **Ternary Operator**
   ```javascript
   condition ? expression1 : expression2;
   ```

4. **Switch Case**
   ```javascript
   switch (variable) {
       case "1":
           // code to be executed if variable is "1"
           break;
       case "2":
           // code to be executed if variable is "2"
           break;
       default:
           // code to be executed if variable doesn't match any case
   }
   ```

## Output Methods
1. `prompt("output")`: Displays a dialog box with a message and an input field for the user.
2. `alert("output")`: Displays an alert box with a message and an OK button.
3. `console.log("output")`: Prints a message to the browser console for debugging.
4. `console.error("error message")`: Prints an error message to the browser console.
5. `console.warn("warning message")`: Prints a warning message to the browser console.
6. `document.write("output")`: Writes content directly into the HTML document.
7. `document.getElementById("demo").innerHTML = "output"`: Sets the content of an HTML element with the specified id.

## TypeCasting
Typecasting is converting a value from one data type to another. It can be implicit or explicit.

### Examples:
```javascript
let a = "123";
a = Number.parseInt(a); // Convert string to a number
a = parseInt(a); // Convert string to a number
```

## Loops
### 1. for
```javascript
for (initialize; condition; increment) {
  // code to be executed
}
```

### 2. for-in
Iterates over the properties of an object.
```javascript
const dict = {
  water: "pani",
  lens: "chasma",
  bag: "basta",
  mobile: "phone"
};

for (let key in dict) {
  console.log(key); // prints keys
  console.log(dict[key]); // prints values
}
```

### 3. for-of
Iterates over the values of an iterable object.
```javascript
let name = "sanskar";
for (let char of name) {
  console.log(char); // prints each character
}
```

### 4. while
```javascript
while (condition) {
  // code to be executed
}
```

### 5. do-while
```javascript
do {
  // code to be executed
} while (condition);
```

## Functions
Reusable blocks of code that perform specific tasks.

### Function without Parameters
```javascript
function funcName() {
  // code to be executed
}
funcName(); // calling the function
```

### Function with Parameters
```javascript
function myFunc(a, b) {
  return a + b;
}
```

### Arrow Function
```javascript
// Before Arrow Function
funcName = function() {
  return "Hello World!";
}

// After Arrow Function
funcName = () => "Hello World!";
```

## Strings
1. `"Hello my value is " + a` // double quotes
2. `'Hello my value is ' + a` // single quotes
3. ``Hello my value is ${a}`` // backticks (template literals)

### Escape Sequences
- `\n`: New line
- `\t`: Tab
- `\'`: Single quote
- `\"`: Double quote
- `\\`: Backslash

### String Methods
- `strName.charAt(index)` or `strName[index]`: Returns the character at the specified index.
- `strName.charCodeAt(index)`: Returns the Unicode value of the character at the specified index.
- `String.fromCharCode(CharCodeOfString)`: Returns a string from the Unicode value.
- `strName.endsWith("text")`: Checks if the string ends with a specific value.
- `strName.includes("text")`: Checks if the string contains a specific value.
- `strName.indexOf("text")`: Returns the index of the first occurrence of the given string.
- `strName.lastIndexOf("text")`: Returns the index of the last occurrence of the given string.
- `strName.length`: Returns the length of the string.
- `strName.localeCompare("text2")`: Compares two strings and returns -1, 0, or 1.
- `strName.match(/text/)`: Returns the matched string if found.

### Example:
```javascript
let strName = "Hello World";
console.log(strName.charAt(4)); // Output: "o"
console.log(strName.charCodeAt(6)); // Output: 87
console.log(String.fromCharCode(72)); // Output: "H"
console.log(strName.endsWith("World")); // Output: true
console.log(strName.includes("lo")); // Output: true
console.log(strName.indexOf("o")); // Output: 4
console.log(strName.lastIndexOf("o")); // Output: 7
console.log(strName.length); // Output: 11
console.log(strName.localeCompare("Hello")); // Output: 1
console.log(strName.match(/World/)); // Output: ["World"]
```

### Splitting a String into an Array
```javascript
let text = "a,b,c,d,e,f";
let myArray = text.split(",");
console.log(myArray[2]); // Output: "c"
```

## Arrays
- `const array = []`
- `let array = []`

### Array Methods
1. **`push()`**
   - Adds one or more elements to the end of an array and returns the new length.
   ```javascript
   let arr = [1, 2, 3];
   arr.push(4);
   console.log(arr); // [1, 2, 3, 4]
   ```

2. **`pop()`**
   - Removes the last element from an array and returns that element.
   ```javascript
   let arr = [1, 2, 3, 4];
   arr.pop();
   console.log(arr); // [1, 2, 3]
   ```

3. **`shift()`**
   - Removes the first element from an array and returns that element.
   ```javascript
   let arr = [1, 2, 3, 4];
   arr.shift();
   console.log(arr); // [2, 3, 4]
   ```

4. **`unshift()`**
   - Adds one or more elements to the beginning of an array and returns the new length

.
   ```javascript
   let arr = [1, 2, 3, 4];
   arr.unshift(0);
   console.log(arr); // [0, 1, 2, 3, 4]
   ```

5. **`splice()`**
   - Adds/removes elements from an array.
   ```javascript
   let arr = [1, 2, 3, 4];
   arr.splice(2, 1, 10);
   console.log(arr); // [1, 2, 10, 4]
   ```

6. **`slice()`**
   - Returns a shallow copy of a portion of an array.
   ```javascript
   let arr = [1, 2, 3, 4];
   let newArr = arr.slice(1, 3);
   console.log(newArr); // [2, 3]
   ```

7. **`concat()`**
   - Merges two or more arrays.
   ```javascript
   let arr1 = [1, 2];
   let arr2 = [3, 4];
   let newArr = arr1.concat(arr2);
   console.log(newArr); // [1, 2, 3, 4]
   ```

8. **`join()`**
   - Joins all elements of an array into a string.
   ```javascript
   let arr = [1, 2, 3, 4];
   let str = arr.join("-");
   console.log(str); // "1-2-3-4"
   ```

9. **`map()`**
   - Creates a new array with the results of calling a provided function on every element.
   ```javascript
   let arr = [1, 2, 3, 4];
   let newArr = arr.map(x => x * 2);
   console.log(newArr); // [2, 4, 6, 8]
   ```

10. **`filter()`**
    - Creates a new array with all elements that pass the test implemented by the provided function.
    ```javascript
    let arr = [1, 2, 3, 4];
    let newArr = arr.filter(x => x > 2);
    console.log(newArr); // [3, 4]
    ```

11. **`reduce()`**
    - Executes a reducer function on each element, resulting in a single output value.
    ```javascript
    let arr = [1, 2, 3, 4];
    let sum = arr.reduce((acc, curr) => acc + curr, 0);
    console.log(sum); // 10
    ```

12. **`sort()`**
    - Sorts the elements of an array.
    ```javascript
    let arr = [4, 2, 3, 1];
    arr.sort();
    console.log(arr); // [1, 2, 3, 4]
    ```

13. **`reverse()`**
    - Reverses the elements in an array.
    ```javascript
    let arr = [1, 2, 3, 4];
    arr.reverse();
    console.log(arr); // [4, 3, 2, 1]
    ```

14. **`find()`**
    - Returns the value of the first element that satisfies the provided testing function.
    ```javascript
    let arr = [1, 2, 3, 4];
    let found = arr.find(x => x > 2);
    console.log(found); // 3
    ```

15. **`findIndex()`**
    - Returns the index of the first element that satisfies the provided testing function.
    ```javascript
    let arr = [1, 2, 3, 4];
    let index = arr.findIndex(x => x > 2);
    console.log(index); // 2
    ```

## Window Object
The window object represents the browser's window. It contains various properties and methods.

### Common Methods
- `alert("Hello, World!");`
- `prompt("Enter your name:");`
- `confirm("Are you sure?");`

### Timer Methods
- `setTimeout(function, milliseconds)`: Executes a function after a specified number of milliseconds.
- `setInterval(function, milliseconds)`: Repeats execution of a function continuously every specified number of milliseconds.

### Example:
```javascript
setTimeout(() => {
  console.log("Hello after 3 seconds");
}, 3000);

let interval = setInterval(() => {
  console.log("Repeating every 2 seconds");
}, 2000);

// To clear the interval
clearInterval(interval);
```

## DOM Manipulation
The Document Object Model (DOM) allows scripts to update the content, structure, and style of a document.

### Selecting Elements
- `document.getElementById("id")`
- `document.getElementsByClassName("className")`
- `document.getElementsByTagName("tagName")`
- `document.querySelector("selector")`
- `document.querySelectorAll("selector")`

### Modifying Elements
- `element.innerHTML = "New Content"`
- `element.style.property = "value"`
- `element.setAttribute("attribute", "value")`
- `element.classList.add("className")`
- `element.classList.remove("className")`
- `element.classList.toggle("className")`

### Creating and Removing Elements
- `document.createElement("tagName")`
- `element.appendChild(child)`
- `element.removeChild(child)`
- `element.replaceChild(newChild, oldChild)`

### Event Handling
- `element.addEventListener("event", function)`
- `element.removeEventListener("event", function)`

### Example:
```javascript
let button = document.getElementById("myButton");
button.addEventListener("click", () => {
  alert("Button clicked!");
});

let div = document.createElement("div");
div.innerHTML = "Hello, World!";
document.body.appendChild(div);

document.body.removeChild(div);
```

### Adding External JavaScript
Add the following line in your HTML file inside the `<head>` or `<body>` tag:
```html
<script src="filename.js"></script>
```

This concludes the LearnJS summary of fundamental JavaScript concepts and syntax.
