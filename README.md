# learning-functional-programming

### Repository description
Repository for learning functional programming with JS.

### 📘 Definition of functional programming

> Functional programming is a programming paradigm — a style of building the structure and elements of 
> computer programs — that treats computation as the evaluation of mathematical functions and avoids 
> changing-state and mutable data — Wikipedia

### Summary
- Pure functions
- Immutability
- Functions as first-class entities
- Higher-order functions

### Pure functions
What does make a function pure?
- deterministic: It returns the same result if given the same arguments.
- There are not side effects
Tips:
- Any function that relies on a random number generator can not be pure.
- Presence of const key word.
- It returns someting instead of just cause some side effect like console.

#### Immutability
When data is immutable, its state can not change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

### Functions as first-class entities
- You can refer to it from constants and variables
- You can pass it as a parameter to other functions
- You can return it as result from other functions

### Higher-order functions
It means a function that either:
- takes one or more functions as arguments, or
- returns a function as its result
Examples:
- Map
- Filter
- Reduce

### 📰 References
- [FreeCodeCamp Article](https://www.freecodecamp.org/news/functional-programming-principles-in-javascript-1b8fc6c3563f/)
- [OpenSource Article](https://opensource.com/article/17/6/functional-javascript)
