# Day 51

## What does Inheritance accomplish for us in C#?
One aspect of inheritance is code reuse. You can avoid defining the same methods and properties repeatedly. Inheritance also gives identity to a class, establishing a relationship between base and derived class.

## How does Member inheritance work in C#? Does a class inherit all members of the base class?
A class inherits the members that it has appropriate access to. The child class can use its parent members as if it were that parent class.

## How does accessibility affect inheritance?
Private members are not accessible from child classes, unless the child class is nested in the parent class. Protected members of a parent class are only accessible from child classes.

https://github.com/TimZaleski/legoapi