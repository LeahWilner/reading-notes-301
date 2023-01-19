# Class 3

## React Docs - lists and keys

1. What does .map() return?  
A new array from calling a function on a previously called array

2. If I want to loop through an array and display each value in JSX, how do I do that in React?  
Use a callback function

3. Each list item needs a unique _key___.  

4. What is the purpose of a key? 
To give the elements in an array a stable identity 

## The Spread Operator

1. What is the spread operator?  
It expands an iterable object into the list of arguments

2. List 4 things that the spread operator can do.  
Copy an array, use math functions, adding to state in React, combine objects

3. Give an example of using the spread operator to combine two arrays. 
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray] 

4. Give an example of using the spread operator to add a new item to an array.  

const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]

5. Give an example of using the spread operator to combine two objects into one.  

const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo}