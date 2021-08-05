# FUNCTIONAL PROGRAMMING

[home](/README.md)

# Reading
## Functional Programming Concepts

### What is functional programming?
A style of building the structure and elements of computer programs. It treats computation as the evaluation of mathematical functions and avoids changing state and mutable data.

### What is a pure funcion and how do we know if something is a pure function?
It is a function that returns the same results if given the same arguments and does not cause observable side effects. If it reads external files it is not a pure function. A function that relies on a random number generator is not pure either.

### What are the benefits of a pure function?
It is easier to test, stable, consistent and predictable. Pure functions will always return the same results.

### What is immutability?
When data is immutable, its state cannot change after its created. It is unchanging over time or unable to be changed.

### What is Referential transparency?
If a function consistently yields the same result for the same input it is considered a referential transparency. 
pure functions + immutable data = referential transparency

# Video
## Node Js Tuttorial for Beginners #6- Modules and require()


### What is a module?
It is essentially another JavaScript file. Can have multiple .js files to do seperate tasks

### What does the word 'require' do?
It creates a path to a module that you require.
require('./filename');

### How do we bring another module into the file that we are working in?
You would type module.export at the bottom of the file you want to bring in. Then on the file you are working on type at the top of the page require('./filename'); It will then bring in another module into the file that you are working on.

### What do we have to do to make a module available? 
Use the exports keyword to make properties and methods available.


## Things I want to know more about
