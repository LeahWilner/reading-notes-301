# Class 5

## React Docs - Thinking in React

1. What is the single responsibility principle and how does it apply to components?  
A component should do one thing and if it grows, it should be broken up into smaller subcomponents.  

2. What does it mean to build a ‘static’ version of your application?  
To build a version without interactivity that doesn't use state

3. Once you have a static application, what do you need to add? 
Interactivty through state 

4. What are the three questions you can ask to determine if something is state? 
Is it passed from a parent through props? Does it remained uncahnged over time? Can you compute it based on any other props or state in your component? 

5. How can you identify where state needs to live?  
Identify every component that renders something based on state, find a common owner, follow the hierarchy, create a new component solely for holding state and add it in the hierarchery above the common owner

## Higher-Order Functions

1. What is a “higher-order function”?
Functions that operate on other functions by taking them as arguments or returning them  

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing? 
Returing m, where m is greater than n  

3. Explain how either map or reduce operates, with regards to higher-order functions.  
The map transforms all the elements in an array and returns a new array, the elements of the new array are mapped by the function
