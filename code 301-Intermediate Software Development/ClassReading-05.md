# Putting it all Together

[home](/README.md)

## React Docs-Thinking in React

### How would you break a mock into a component heirarchy?
Start with drawing boxes around every component and subcomponent in the mock and give them all names. Components in the mock should appear within another component in the mock should appear as a child in the hierarchy.

### What is the single responsibility principle and how does it apply to components?
Components should do only one thing. If it ends up growing, it should be broken up into smaller subcomponents.

### What does it mean to build 'static version of your application?
A version of your application that takes data model and renders the UI but has no interactivity.

### Once you have a static application, what do you need to add?
You need to be able to trigger changes to you runderlying data model. So you need to start adding state to start making it interactive.

### What are the three questions you can ask to determine if something is state?
<ul>
<li>Is it passed from a parent via props?.. If so, it probably isnt state.</li>
<li>Does it remain unchanged overtime?.. Propably isn't state.</li>
<li>Can you compute it based on any other state or props in your component? If so, it isn't state.</li>
</ul>

### How can you identify where state neeeds to live?
<ul>
<li>Identifiy every component that renders something based on that state</li>
<li>Find a common owner component (a single component above all the components)</li>
<li>Either the common owner or another component higher up in the hierarchy should own the state</li>
<li>If you can't find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.</li>
</ul>






## Things I want to know more about
