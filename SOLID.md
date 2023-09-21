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
