# Class Activity 1

Welcome to CS 491 - Testing and DevOps! Your first assignment is outlined below:
## Project Goals
The goal of this project is to:
1. Review basic Object Oriented Principles
2. Allow students to explore using the Python programming language

## Program
Use Vehicles to explore how to implement OOP in Python.

#### Encapsulation  
- Implement a simple Car class and a Bicycle class.
  - Include constructors and useful properties (color, name) for each class.
  - Consider useful methods (start(), pedal()) for each class.  
#### Inheritance
- Both classes should inherit from a Vehicle class.  
#### Best Practices
- Use a main method to instantiate each class and call functions.
- Each class definition should be in a separate file.
- Often classes are composed with other classes, for example, a Car and Bike both have Wheels or a Car has an Engine.
  - Create classes for each entity and use composition to add them to your Car or Bicycle class (you may use the same Wheel class for Cars and Bikes)
#### Polymorphism
- Outside of C++, polymorphism generally refers to runtime polymorphism
  - we would demonstrate that by creating a Vehicle object and assigning a Car to it, calling a function, then assigning a Bicycle object to it and calling the function again.
- If did that in Python, would that be Polymorphism?
  - Why or why not?

### Requirements
1. .py files for each class and the main driver
2. a text document with you and your reflections on polymorphism and Python

## Submission details
To submit your project, you will have to use git on your VirtualBox installation:
1.	After accepting the assignment invitation, copy the clone URL
2.	Type 
```git clone clone URL```
3.	cd into your new assignment directory
4.	After working on your files
5.	When you’re ready, type the following commands: 
```
git add .
git commit -m “your commit message”
git push
```
