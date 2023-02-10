# Class 37 Reading Notes

## REACT Review 1

### ES6 Syntax/Features

- Arrow Functions: a shorter way of creating a function expression. Arrow functions do not have their own this, do not have prototypes, cannot be used for constructors, and should not be used as object methods. ex: let func = (a, b, c) => {} // parentheses required with multiple parameters
- Template Literal: let str = `Release Date: ${date}`
- The Spread operator expands an array: let arr3 = [...arr1, ...arr2] output: [1, 2, 3, "a", "b", "c"]

### REACT

- JSX: Used to write HTML in JavaScript. ex: ```const element = <h1>Hello, {name}</h1>;```
- Have to pass props between different compnents in order to gett access to their data
- Use state to keep track of and interact with data on the webpage
- you can create functions that handle evens in react similar to normal DOM manipulation

### Next.JS

- NextJs is a react framework
Next.js features:
- An intuitive page-based routing system
- Pre-rendering, both static generation (SSG) and server-side rendering (SSR) are supported on a per-page basis
- Automatic code splitting for faster page loads
- Client-side routing with optimized prefetching
- Built-in CSS and Sass support, and support for any CSS-in-JS library
- Development environment with Fast Refresh support
- API routes to build API endpoints with Serverless Functions

---

### Resources

[ES6 Syntax Review](https://www.taniarascia.com/es6-syntax-and-feature-overview/)

[REACT Overview](https://reactjs.org/docs/hello-world.html)

[NExt.JS](https://nextjs.org/learn/basics/create-nextjs-app)

---

[Back to Home](../README.md)
