# Read: Class 03

## What does .map() return?

* return new array

## If I want to loop through an array and display each value in JSX, how do I do that in React?

* use map function to loop all index

## Each list item needs a unique?

* key

## What is the purpose of a key?

* Keys help React identify which items have changed, are added, or are removed.

## What is the spread operator?

* the spread operator in javascript syntax is short and quick combining arrays or objects, and spreading an array out into a function’s arguments we use for it use of an ellipsis of three dots

## List 4 things that the spread operator can do?

* Concatenating or combining arrays
* Using an array as arguments
* Adding to state in React
* Converting NodeList to an array

## Give an example of using the spread operator to combine two arrays.?

* const Arr1 = [ 13 , 23 , 33 ] const Arr2 = [ 3 , 7 , 13 ] const Arr = [...Arr1,...Arr2]

## Give an example of using the spread operator to add a new item to an array?

* const arr1 = ['A','B','C'] const arr2 = ['D', 'E', ...arr1]

## Give an example of using the spread operator to combine two objects into one?

* const arr1 = {hi: "test"} const arr2 = {all: "test2"} const arr3 = {...arr1, ...arr2 }

## what is the first step that the developer does to pass functions between components?

* create objects

## In your own words, what does the increment function do?

* when click the button the state will be update and increase the count one

## How can you pass a method from a parent component into a child component?

* using the props to move the properties from one component to other

## How does the child component invoke a method that was passed to it from a parent component?

* through extend then import child page to parent page to send the methods propties
