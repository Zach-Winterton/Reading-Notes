# Passing Functions as Props

[home](/README.md)

## React Docs-Lists & Keys

### What does .map() return?
A new array populated with the results

### If I want to loop through an array and display each value in JSX, how do I do that in React?
const numbers = [1,2,3,4,5];
const listItems = numbers.map((number) =>
<*li>{number}</*li>
);

### Each list item needs a unique ____.
key

### What is the purpose of a key?
Keys help identify which items have changed, are added or removed. Given to elements inside the array to give spread operator a stable identity.


## The Spread Operator

### What is the spread operator?
The use of an ellipsis of three dots (...) to expand an iterable object into the list of arguments..It "spreads" the array into seperate arguments. 
math.max(...[1,3,5])
### List 4 things that the spread operator can do.
<ul>
<li>combining objects</li>
<li>adding to State in React</li>
<li>using an array as arguments</li>
<li>using math functions</li>
</ul>

### Give an example of using the spread operator to combine two arrays.
const myNumbers = [1,2,3]
const otherNumbers = [6,7,8]
const allNumbers = [...myNumbers,...otherNumbers]
console.log(allNumbers)

### Give an example of using the spread operator to add a new item to an array.
const numbers = [4,5,6]
const moreNumbers = [7,8,...numbers]
console.log(moreNumbers)


### Give an example of using the spread operator to combine two objects into one.
const object = {Hi:""}
const otherObject = {Hello:""}
const lastObject = {...object,...otherObject,}
console.log(lastObject)

## How to Pass Functions Between Components

### In the video, what is the first step that the developer does to pass functions between components?
Create a function

### In your own words, what does the increment function do?
increases the count number by whatever chosen multiplier,addition, subtraction etc

### How can you pass a method from a parent component into a child component?
this.method name

### How does the child component invoke a method that was passed to it from a parent component?
this.props.method name

## Things I want to know more about
