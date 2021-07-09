# Introduction to React and Components

[home](/README.md)

## Component based Architecture

### What is a Component?
A component is a modular, portable replaceable and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface. It's also a software object, intended to interact with other components. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture.

### What are the charactistics of a component?

<ul>
<li>Reusability- Components are ususally designed to be reused in different situations in different applications. However, some components may be designed for a specific task</li>
<li>Replaceable- Components may be freely substituted with other similar components.</li>
<li>Not context specific- Components are designed to operate in different environments and contexts.</li>
<li>Extensible- A component can be extended from existing components to provide new behavior.</li>
<li>Encapsulated- A component depitcs the interfaces, which allow the caller to use its functionality, and do not expose details of the internal variables or state.</li>
<li>Independent- Components are designed to have minimal dependencies on other components.</li>
</ul>

### What are the advantages of using component based architecture?
<ul>
<li>Ease of deployment- As new compatible versions become available, it is easier to replace exsiting versions with no impact on the other components or the system as a whole.</li>
<li>Reduced cost- The use of third-party components allows you to spread the cost of development and maintence.</li>
<li>Ease of development- Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.</li>
<li>Reusable- The use of reusable components meanst that they can be used to spread the development and maintenance cost across several applications or systems.</li>
<li>Modification of technical complexity- A component modifies the complexity through the use of a component container and its services.</li>
<li>Reliabilty- The overall system reliabilty increases since the reliability of each individual component enhances the reliability of the whole system via reuse.<li>
<li>System maintenence and evolution- Easy to change and update the implementation without affecting the rest of the system. </li>
<li>Independent- Independency and flexible connectivity of components. Independent development of Components by different group in parallel. Productivity for the software development and future software development.<li>
</ul>

## What is Props and how to use it in React?

### What is props short for?
Props is a special keyword in React, Which stands for properties and is being used for passing data from one component to another.

### How are props used in React?
<ul>
<li>Define an attribute and its value(data)</li>
<li>Then pass it to a child components by using Props.</li>
<li>Finally, Render the Props data.</li>
</ul>

### What is the flow of Props?
Props can only be passed to components in one-way(parent to child).

## Things I want to know more about
