# SOLID
- S : Single Responsibility Principle 
- O : Open/Closed Principle
- L : Liskove's Substitution Principle 
- I : Interface Segregation Principle
- D : Dependency Iversion Principle
## S : Single Responsibility Principle 
One of the SOLID principles of object-oriented programming is the Single Responsibility Principle (SRP). It says that a class should only have one cause to change, or, to put it another way, only have one responsibility.

A class that manages both data storage and user authentication, for instance, violates SRP. Instead, distinct classes with a single duty for each should be used for user authentication and data storage. Because of this division, it is simpler to update or expand each component of the system without affecting the others.

## O : Open/Closed Principle
One of the SOLID principles of object-oriented programming is the Open/Closed Principle (OCP). According to this, software elements like classes, modules, and functions should be accessible to expansion but closed to alteration. One can adhere to the OCP by adding new shape classes and area calculation methods without changing the old shape class, for instance, if a class represents several shapes and their area calculation methods. By doing so, it increases functionality while keeping the present code closed to changes.

## L - Liskov Substitution Principle
The Liskov Substitution Principle (LSP) states that subclasses should be able to substitute their base classes without breaking the functionality or expectations of the system. This means that you should design your subclasses in a way that they respect the contract and behavior of their base classes, and do not introduce any unexpected side effects or violations. For example, if you have a class that represents a rectangle, and a subclass that represents a square, you should not override the methods that set the width and height of the rectangle, as this would break the logic and consistency of the system. By applying the LSP, you can ensure low coupling and high cohesion, as your modules will be more consistent, reliable, and interchangeable.

## I - Interface Segregation Principle

The Interface Segregation Principle (ISP) states that clients should not be forced to depend on interfaces that they do not use. This means that you should design your interfaces in a way that they are small, focused, and specific, and not large, general, and bloated. For example, if you have an interface that defines methods for reading, writing, and deleting files, you should split it into smaller interfaces that correspond to each operation, and let the clients implement only the ones that they need. By applying the ISP, you can achieve low coupling and high cohesion, as your modules will be more modular, decoupled, and cohesive.

## D- Dependency Inversion Principle

The Dependency Inversion Principle (DIP) states that modules should depend on abstractions, not on concretions. This means that you should design your modules in a way that they rely on interfaces or abstract classes, rather than on concrete classes or implementations. For example, if you have a class that depends on a database class, you should inject an interface or an abstract class that defines the methods for accessing the database, rather than creating an instance of the database class directly. By applying the DIP, you can achieve low coupling and high cohesion, as your modules will be more loosely coupled, testable, and adaptable.
