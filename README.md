# Hello
## My 
### Name 
#### Is 
##### Nataliia
###### h6


I'm Ukranian **bold**. Here I'm also Ukranian __bold__.

This text is in *italics*. This text is also in _italics_.
This text is ***bold and italicized***. This text is also ___bold and italicized___.




EXERCISE

# h1 Writing a Function in JavaScript
![Computer with Code](/modular-curriculum-all-courses/intro-to-markdown-lab/exercise/assets/james-harrison-unsplash.jpg)

 In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## 1. Basic syntax


1. **const**: functionName = (params) => {
  // code to be executed
}

 const: const should be used whenever a function expression is assigned to a variable.
2.  **The function name**: The name you choose for the function.
3. **Parameters**: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
4. **The arrow syntax**: Indicates that this will be a function.
5. **The body**: The statements that make up the function itself. Surrounded by curly braces.

## Example:
```javascript
const greet = (name) => {
  console.log("Hello, " + name + "!");
}
```
>Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

## 2. Calling a function
```markdown
To execute the function, you *call* or *invoke* it by using its name followed by parentheses.
```
Example:
```javascript
greet('Alice'); // Outputs: Hello, Alice!
```
## 3. Return values

Functions can process data input and output a value using the *return* keyword.

**_Example_**: 

const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6
```markdown
### For more information on functions and how they are used in JS, check out the MDN docs. 
[MDN Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)
```

