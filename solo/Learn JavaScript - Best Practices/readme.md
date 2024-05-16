# Learn JavaScript: Best Practices

https://www.codecademy.com/courses/learn-javascript-best-practices/articles/javascript-currying
Learn how JavaScript works under the hood and level up your code composition with various design patterns.

Syllabus

# JavaScript Under the Hood

## Currying in JavaScript

Currying is a functional programming technique.

This article will discuss currying, a functional programming technique we can use to write code that is modular, easy to test, and highly reusable. Functional programming is a declarative paradigm that emphasizes immutability and pure functions — meaning the function is side-effect free and for any given input it will always return the same output.

This helps make code more readable and easier to reason about in general, and currying is just one part of it. Let’s get started with currying!

How currying works
In order to understand the point of currying and how it works, we can first look at a non-curried function.

Below, we’ve created a non-curried function add(). add() will still execute if called with a missing argument, which would result in the missing variable being evaluated as undefined. For the add() function below, if add() was called with an argument for a but not for b, the function call would evaluate as 1 + undefined and return NaN. That’s not great and could be tricky to debug in practice.

Let’s curry the add() function to see how we can handle the function call better if only one argument is available. What we can do is transform the add() function, which normally expects multiple arguments, into a series of nested functions that will each take a single argument.

This makes the function calls more modular. With curried functions, calling the outer function returns the next function in the chain and so on until the innermost function is called, which then returns a value.

In code that would look like this:

```
// traditional function
function add(a,b) {
    return a + b;
} ```

```
// curried function
function curried_add(a) {
    // The outer function returns a nested single-argument function
    return function nested_func(b) {
        return a + b;
   }
} ```

What we did in the code is declare curried_add() as a function that takes a single argument and returns another function named nested_func(). (The returned function can also be anonymous, but has a name in this example for clarity.)

- Calling the outer function curried_add() returns nested_func().
- Calling nested_func uses the arguments supplied from calling curried_add and nested_func to return the evaluated result of a + b.

*** Lexical Scoping defines how variable names are resolved in nested functions: inner functions contain the scope of parent functions even if the parent function has returned. 
The last part: "even if the parent function has returned" is called Closure. ***

## Hoisting in JavaScript

## Concurrency Model and Event Loop in JavaScript

## Introduction to Memory Management in JavaScript

## Debugging Memory Issues in JavaScript

## Learn about best practices and design patterns in JavaScript.


## JavaScript Best Practices

## Design Patterns in JavaScript

## Informational Next Steps