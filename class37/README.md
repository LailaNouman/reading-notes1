# Class-37:

### ES6 Syntax and Feature
ECMAScript 2015, also known as ES6, introduced many changes to JavaScript.

- ES6 introduced the let keyword, which allows for block-scoped variables which cannot be hoisted or redeclared, and introduced the const keyword, which cannot be redeclared or reassigned, but is not immutable.
- Arrow functions: The arrow function expression syntax is a shorter way of creating a function expression. Arrow functions do not have their own this, do not have prototypes, cannot be used for constructors, and should not be used as object methods.
- Using template literal syntax, a JavaScript string can span multiple lines without the need for concatenation. (Note: Whitespace is preserved in multi-line template literals.)
- The return keyword is implied and can be omitted if using arrow functions without a block body.
- ES6 introduces a shorter notation for assigning properties to variables of the same name.
- The function keyword can be omitted when assigning methods on an object.

And there more and more features inside it.

### JSX 
A syntax is neither a string nor HTML, it is called JSX, and it is a syntax extension to JavaScript. We recommend using it with React to describe what the UI should look like. JSX may remind you of a template language, but it comes with the full power of JavaScript.

- Why JSX: React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display, instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled units called “components” that contain both. 