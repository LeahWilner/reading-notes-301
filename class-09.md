# Class 9  

## Functional Programming Concepts

1. What is functional programming?  
Functional programming is a programming paradigm that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data  

2. What is a pure function and how do we know if something is a pure function?  
It returns the same result if given the same arguments and It does not cause any observable side effects  

3. What are the benefits of a pure function?  
It's easier to test so unit testing can be used  

4. What is immutability?  
Data with a state that cannot change after it’s created  

5. What is Referential transparency?  
pure functions + immutable data = referential transparency  

## Node JS Tutorial for Beginners #6 - Modules and require()

1. What is a module?  
Just another JavaScript file, it helps with organizing files  

2. What does the word ‘require’ do?  
Allows a path to a module  

3. How do we bring another module into the file the we are working in?  
var countCats = require ('./anotherModule');  

4. What do we have to do to make a module available?  
module.exports = countCats  
