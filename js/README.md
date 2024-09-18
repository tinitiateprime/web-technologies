![JS Tinitiate Image](js_tinitiate.png)

# JS Tutorial
&copy; TINITIATE.COM

##### [Back To Context](../README.md)

## CONTEXT
**1. Introduction to JavaScript**  
- **Keywords** :
  - JavaScript

  - Client-side scripting

  - Server-side scripting

  - ECMAScript (ES)

  - Syntax

  - Browser console

  - Console API (console.log, console.error, console.warn)
 
  - HTML integration (`<script>` tag)
 
  - External JavaScript file (`<script src="file.js"></script>`)
**2. JavaScript Basics**  
- **Syntax and Comments** 
  - Syntax

  - Comments (Single-line, Multi-line)
 
- **Variables and Data Types** 
  - Variable declaration (var, let, const)

  - Data types: String, Number, Boolean, Undefined, Null, Symbol

  - Variable scope (Global, Local)

  - Hoisting
 
- **Operators**  
  - Arithmetic operators: `+`, `-`, `*`, `/`, `%`, `++`, `--`
 
  - Assignment operators: `=`, `+=`, `-=`, `*=`, `/=`, `%=`
 
  - Comparison operators: `==`, `===`, `!=`, `!==`, `>`, `<`, `>=`, `<=`
 
  - Logical operators: `&&`, `||`, `!`
 
  - Conditional (Ternary) operator: `condition ? value1 : value2`
 
- **Type Conversion and Type Coercion**  
  - Explicit conversion: `Number()`, `String()`, `Boolean()`, `parseInt()`, `parseFloat()`

  - Implicit conversion (type coercion)
**3. Control Flow**  
- **Conditional Statements** 
  - if statement

  - else if statement

  - else statement

  - Switch statement (switch, case, break, default)
 
- **Loops** 
  - for loop

  - while loop

  - do-while loop

  - Nested loops
 
- **for...in and for...of Loops** 
  - for...in (Iterating over object properties)

  - for...of (Iterating over iterable objects like arrays)
 
- **Break and Continue** 
  - break statement

  - continue statement
**4. Functions**  
- **Function Declaration and Expression**  
  - Function declaration: `function myFunction() {}`
 
  - Function expression: `const myFunction = function() {}`
 
- **Parameters and Arguments** 
  - Function parameters (Default parameters)
 
  - Rest parameters: `function(...args)`

  - Arguments object
 
- **Returning Values** 
  - return statement
 
- **Arrow Functions (ES6)**  
  - Arrow function syntax: `const myFunction = () => {}`

  - Implicit return in arrow functions
 
- **Function Scope** 
  - Block scope

  - Lexical scope
 
- **Closures** 
  - Closure concept: Inner function retaining access to outer function variables
 
- **Immediately Invoked Function Expression (IIFE)**  
  - IIFE syntax: `(function() {})()`
**5. Arrays and Objects**  
- **Arrays**  
  - Creating arrays: `[]`

  - Accessing array elements

  - Modifying arrays
 
  - Array methods: `push()`, `pop()`, `shift()`, `unshift()`, `splice()`, `slice()`, `concat()`, `map()`, `filter()`, `reduce()`, `forEach()`, `find()`, `findIndex()`, `indexOf()`, `includes()`, `sort()`, `reverse()`, `join()`, `split()`

  - Iterating over arrays
 
- **Objects**  
  - Creating objects: `{ key: value }`

  - Accessing object properties (Dot notation, Bracket notation)

  - Adding/updating properties
 
  - Deleting properties: `delete object.property`

  - Object methods

  - Object.keys(), Object.values(), Object.entries()

  - Object.assign()
 
- **Destructuring**  
  - Array destructuring: `[a, b] = [1, 2]`
 
  - Object destructuring: `{key1, key2} = {key1: 'value1', key2: 'value2'}`
 
- **Spread and Rest Operators**  
  - Spread operator: `...`
 
  - Rest parameters: `function(...args)`

- **Sets and Maps**

**6. Working with the DOM (Document Object Model)**  
- **DOM Manipulation**  
  - Selecting elements: `getElementById()`, `getElementsByClassName()`, `getElementsByTagName()`, `querySelector()`, `querySelectorAll()`
 
  - Modifying content: `innerHTML`, `textContent`, `value`
 
  - Modifying attributes: `setAttribute()`, `getAttribute()`, `removeAttribute()`
 
  - Modifying styles: `style.property`, `classList.add()`, `classList.remove()`, `classList.toggle()`
 
  - Creating elements: `createElement()`
 
  - Appending elements: `appendChild()`, `insertBefore()`
 
  - Removing elements: `removeChild()`, `remove()`
 
- **Event Handling**  
  - Adding event listeners: `addEventListener()`
 
  - Event types: `click`, `mouseover`, `mouseout`, `keyup`, `keydown`, `submit`, `change`, `input`, `focus`, `blur`
 
  - Event object: `event.target`, `event.type`, `event.preventDefault()`, `event.stopPropagation()`

  - Event propagation: Event bubbling, Event capturing

  - Event delegation
**7. Error Handling and Debugging**  
- **Errors in JavaScript** 
  - Types of errors: Syntax errors, Runtime errors, Logical errors
 
- **Try-Catch-Finally**  
  - `try` block
 
  - `catch` block
 
  - `finally` block
 
  - Throwing custom errors: `throw new Error()`
 
- **Debugging**  
  - `console.log()`
 
  - `console.error()`
 
  - `console.warn()`
 
  - `debugger`

  - Browser developer tools (Chrome DevTools)
**8. Advanced JavaScript Concepts**  
- **Asynchronous JavaScript** 
  - Callbacks
 
  - Promises: `Promise()`, `resolve()`, `reject()`, `then()`, `catch()`
 
  - Async/Await: `async`, `await`
 
  - Error handling in promises (chaining with `.catch()`)
 
- **Modules (ES6)**  
  - Exporting modules: `export default`, `export { named }`
 
  - Importing modules: `import module from 'module'`, `import { named } from 'module'`
 
- **Prototypes and Inheritance** 
  - Prototype chain

  - Prototypal inheritance
 
  - Creating objects with `Object.create()`

  - Constructor functions
 
  - ES6 Classes: `class`, `constructor()`, `extends`, `super()`
 
- **Closures** 
  - Closures (Inner functions accessing outer variables)
**9. JavaScript in the Browser**  
- **JavaScript in the Browser**
  - Browser object model (BOM)
  - History, location, and navigator objects
  - Cookies and local storage
  - Session storage and indexedDB
- **Timers**  
  - `setTimeout()`
 
  - `setInterval()`
 
  - Clearing timers: `clearTimeout()`, `clearInterval()`
 
- **Web APIs**  
  - Fetch API: `fetch()`

  - XMLHttpRequest (XHR)
 
  - JSON parsing: `JSON.parse()`, `JSON.stringify()`
 
  - `localStorage`, `sessionStorage`: `setItem()`, `getItem()`, `removeItem()`, `clear()`
 
- **Browser Events**  
  - Page load events: `DOMContentLoaded`, `load`, `beforeunload`, `unload`
 
  - Window events: `scroll`, `resize`
 
  - Form events: `submit`, `focus`, `blur`, `input`, `change`
**10. ES6 and Beyond**  
- **ES6+ Features**  
  - Template literals: ``Hello ${name}``

  - Default parameters

  - Arrow functions
 
  - Spread operator: `...`
 
  - Rest parameters: `function(...args)`

  - Destructuring assignment

  - Classes

  - Object property shorthand
 
  - Symbols: `Symbol()`

  - Iterators and generators
 
- **Modern Features**  
  - Optional chaining: `object?.property`
 
  - Nullish coalescing operator: `??`
 
  - BigInt: `BigInt()`
 
  - Private fields in classes: `#privateField`




  - **Advanced Topics**
  - Closures
  - Higher-order functions
  - Callbacks, promises, and async/await
  - Regular expressions
  - Modules (import, export)
- **Best Practices**
  - Writing clean and readable code
  - Avoiding global variables
  - Using strict mode
  - Code linting and formatting tools (ESLint, Prettier)
- **Tools and Frameworks**
  - Node.js and npm
  - JavaScript frameworks and libraries (React, Angular, Vue, jQuery)
  - Build tools (Webpack, Babel)
  - Testing frameworks (Jest, Mocha)
- **Debugging and Testing**
  - Console methods (log, warn, error)
  - Browser Developer Tools
  - Writing and running tests (unit tests, integration tests)

**11. Working with External Libraries**  
- **Including External Libraries**  
  - CDN (`<script>` tags for external libraries)
 
  - npm package installation: `npm install`
 
  - Importing libraries in Node.js: `require()`
 
- **Popular Libraries** 
  - Axios for HTTP requests

  - Lodash for utility functions

  - jQuery for DOM manipulation

  - Moment.js for date manipulation
**12. JavaScript Frameworks (Overview)**  
- **React.js** 
  - Components

  - JSX

  - Props
 
  - State (`useState`)
 
  - Lifecycle methods: `useEffect`
 
  - Hooks (`useState`, `useEffect`, `useReducer`)

  - React Router
 
- **Vue.js** 
  - Vue instance

  - Vue components
 
  - Vue directives: `v-if`, `v-for`, `v-bind`, `v-model`

  - Vue reactive data

  - Vue computed properties

  - Vue methods
 
- **Angular.js** 
  - Components

  - Services

  - Directives

  - Dependency Injection

  - Two-way data binding
**13. JavaScript in Backend (Node.js)**  
- **Introduction to Node.js** 
  - Node.js installation

  - npm (Node package manager)

  - Running JavaScript on the server
 
- **Building a Simple Server**  
  - Using `http` module
 
  - Creating a basic server: `http.createServer()`

  - Routing

  - Serving static files
 
- **Express.js Framework**  
  - Setting up Express: `const express = require('express')`
 
  - Routing in Express: `app.get()`, `app.post()`
 
  - Middleware: `app.use()`

  - Building REST APIs
 
- **Database Interaction** 
  - Connecting to a database (MongoDB, MySQL)

  - CRUD operations (Create, Read, Update, Delete)
**14. Testing JavaScript Code**  
- **Unit Testing** 
  - Jest setup

  - Writing test cases
 
  - Test assertions: `expect()`, `toBe()`, `toEqual()`
 
- **Integration Testing**  
  - Mocking functions: `jest.fn()`

  - Mocking API requests
 
  - Using `supertest` for testing HTTP endpoints
**15. Final Projects**  
- **Frontend Project** 
  - DOM manipulation

  - API integration using Fetch API or Axios

  - Form handling

  - Responsive design
 
- **Full-Stack Project** 
  - REST API with Express.js

  - User authentication (JWT, OAuth)

  - Database integration (MongoDB, MySQL)

  - Frontend with React, Vue, or Angular
 
- **Deployment** 
  - Netlify for frontend deployment

  - Heroku for full-stack deployment
 
  - Git version control: `git add`, `git commit`, `git push`
**16. Bonus: JavaScript Performance and Best Practices**  
- **Performance Optimization** 
  - Minimizing reflows
 
  - Debouncing: `setTimeout()`
 
  - Throttling: `setInterval()`
 
- **Code Readability and Maintainability**  
  - Linters: `ESLint`
 
  - Code formatters: `Prettier`
 
- **Best Practices** 
  - Naming conventions

  - Modular structure
 
- **Security Best Practices** 
  - Preventing Cross-Site Scripting (XSS)

  - Preventing Cross-Site Request Forgery (CSRF)

  - Validating input data

##### [Back To Context](../README.md)
***
| &copy; TINITIATE.COM |
|----------------------|