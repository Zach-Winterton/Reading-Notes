# In Memory Storage

[home](/README.md)

# Reading
## FUnderstanding the JavaScript call Stack

### What is a 'call'?
function invocation

### How many 'calls' can happen at once?
It is one at a time from top to bottom.

### What does LIFO mean?
It means last in, first out. The last function that gets pushed into the stack is the first to be popped out, when the function returns.

### Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
function Hello(){
  console.log("hello");
}
function Ask(){
Hello();
console.log("how are you?");
})
Ask();

### What causes a stack overflow?
A stack overflow occurs when there is a recurrsive function (a function that calls itself) without an exit point.


## JavaScript error messages


### What is a 'reference error'?
When you try to use a variable that is not yet declared a reference error displays.

### What is a 'syntax error'?
Occurs when you have something that cannot be parsed in terms of syntax. A syntax error appears.

### What is a 'range error'?
When you try to manipulate an object with some kind of length and give it an invalid length. A range error appears.

### What is a 'type error'?
This error shows up when the types (number,string and so on) you are trying to use or access are incompatible.

### what is a breakpoint?
It mnakes the program stop at a point only if a condition is met.

### What does the word 'debugger' do in your code?
Allows you to see the history before reaching a breakpoint. Make sure to get rid of all debbugging before a commit/push.


## Things I want to know more about
