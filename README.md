# Class Activity 1
Welcome to CS 333 - Testing and DevOps! Your first assignment is outlined below:

## Project Goals
The goals of this project are to:
1. review basic object oriented principles
2. allow students to explore using the Python programming language

## Program
Use Vehicles to explore applying object oriented principles in Python.

### Best Practices
- Use a main method to instantiate each class and call functions.
- Each class definition should be in a separate file.

## Requirements
1. .py files for each class and the main driver which include each principles as described below
2. a text document with you and your partner's reflections on polymorphism and Python

### Encapsulation  
- Implement a simple Car class and a Bicycle class.
  - Include constructors and useful properties (like `color` or `name`) for each class.
  - Consider useful methods (like `start()` or `pedal()`) for each class.  

### Inheritance
- Both classes should inherit from a Vehicle class.  

### Polymorphism
- Outside of C++, polymorphism generally refers to runtime polymorphism
  - we would demonstrate that by creating a Vehicle object and assigning a Car to it, calling a function, then assigning a Bicycle object to it and calling the function again.
- If you did that in Python, would it be Polymorphism?
  - Why or why not?

### Composition
- Often classes are composed with other classes, for example, a Car and Bike both have Wheels or a Car has an Engine.
  - Create classes for each entity and use composition to add them to your Car or Bicycle class (you may use the same Wheel class for Cars and Bikes)
