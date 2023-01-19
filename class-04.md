# Class 4

## React Docs - Forms

1. What is a ‘Controlled Component’?
An input form element whose value is controlled by React state as the single source of truth

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
Update state with their responses to have a handleChange for capturing every keystroke so you can pass it to other elements or reset it from other event handlers

3. How do we target what the user is entering if we have an event handler on an input field?
target. chained to each input type
event.target.name

## The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?
It can shorten if/else code blocks into one line of code

2. Rewrite the following statement using a ternary statement:

if(x===y){
  console.log(true);
} else {
  console.log(false);


x.y = ((x===y) ? 'Yes' : 'No';)
