# Putting it all together

## React Docs - Thinking in React

What is the single responsibility principle and how does it apply to components?
**a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.**
What does it mean to build a ‘static’ version of your application?
**to build components that reuse other components and pass data using props. Props are a way of passing data from parent to child.**
Once you have a static application, what do you need to add?
**To make the UI interactive, you need to let users change your underlying data model. You will use state for this.**
What are the three questions you can ask to determine if something is state?
**Does it remain unchanged over time? If so, it isn’t state.**
**Is it passed in from a parent via props? If so, it isn’t state.**
**Can you compute it based on existing state or props in your component? If so, it definitely isn’t state!**

How can you identify where state needs to live?
**If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common parent component.**

## Higher-Order Functions

What is a “higher-order function”?
**Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions.**

Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
**returning an arrow function that states that a number is greater than n**
Explain how either map or reduce operates, with regards to higher-order functions.
**The map method transforms an array by applying a function to all of its elements and building a new array from the returned values. The new array will have the same length as the input array, but its content will have been mapped to a new form by the function.**