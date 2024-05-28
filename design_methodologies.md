# Design Methodologies

## What do we mean by coupling and cohesion when discussing structured design?
- Coupling is the degree to which modules are connected to each other. A high degree of coupling means modules a closely interlinked and vice versa.
- Cohesion is the degree to which components within a module work in tandem to achieve a purpose. A high degree of cohesion means the components are closely linked and focused on a single purpose and vice versa. 

## What is the difference between top-down and bottom-up design? Which best describes a function oriented design?
- Top-down design fundamentally starts at a higher level of the system and then goes into more detail. This generally means development happens in a more sequential manner.
- Bottom-down design starts at a point of higher detail of individual components, which are then put together to achieve higher-level functionality. This generally results in a development process where individual components can be
developed independently and simultaneously.
- Function-oriented design is best described by top-down design.

## In which design methodology would a class diagram be most useful?
Object oriented design.

## What are the four pillars of object oriented programming? Give a single-sentence description of each.
**Abstraction** - A technique used to hide implementation of a function in order to simplify it's usage.

**Encapsulation** - A way to implement abstraction by limiting access to certain parts of a function or piece of code (i.e. properties).

**Inheritance** - A way to pass on common features to similar objects without the need to repeat the same code. 

**Polymorphism** - A principle that promotes enabling different classes with the same super class to implement different functionality and have different properties, whilst also sharing some common properties and behaviours.

## What is the strategy pattern? How would its implementation differ between a functional and object oriented system?
- A design pattern that allows for the behaviour of an object to be extracted into seperate classes that can be swapped in and out at runtime.
- In an OOP system, this cam be implemented using classes and interfaces. 
- In a functional system this can be implemented using higer-order functions.

## Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.
- Object-oriented design.
- This methodology is great tool for modelling and implementing real-world systems such as this. With the benefits that come with this such as reusability and flexibility, this will allow for a flexible implementation that can be used across any sector and be able to adapt to changing requirements. With correct implementation and usage of key principles such as inheritance and polymorphism, this can allow for a system that is easily maintainable and scalable.