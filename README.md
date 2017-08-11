# objectOrientedDesignPatterns

# Strategy Design Pattern

 You use this pattern if you need to dynamically change an algorithm used by an object at run time. 
The pattern also allows you to eliminate code duplication. It separates behavior from super and subclasses. 

# Observer Design Pattern

You use this pattern when you need other objects to receive an update when another object changes

# Factory Design Pattern

A method that returns one of several possible classes that share a common super class
i.e. 
create a new enemy in a game

random number generator picks a number assigned to a specific enemy

factory returns an enemy associated with that number 

the class is chosen at runtime

# Abstract Factory Pattern

Like a factory but everything is encapsulated

The method that orders the object
The factories that build the object
The final objects
The final objects contain objects that use the strategy pattern 
Where Object class fields are objects