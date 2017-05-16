# Object Oriented Programming

1. Encapsulation (Information Hiding)
   1. Keeps data and methods safe from outside manipulation or misuse
   2. Provides a stable interface
   3. Makes refactoring easier
2. Inheritance
   1. Allows you to create a new class that reuses, extends, modifies the bahavior of another class
   2. Base class / derived class
   3. Types of classes
      1. Sealed
      2. Abstract
3. Polymorphism
4. Classes
   1. Objects are instances of a class
   2. Properties
   3. Fields (like properties but have get; set; procedures
   4. Methods
      1. Actions an object can perform
   5. Constructors
      1. Initialize the data for a new object
   6. Events
      1. A message sent by an object to signal the occurrence of an action
      2. Subscriber / Provider
   7. Access Modifiers
      1. public
         1. The type or member can be accessed by any other code in the same assembly or another assembly that references it
      2. private
         1. The type or member can only be accessed by code in the same class
      3. protected
         1. The type or member can only be accessed by code in the same class or in a derived class
         2. Similar to "private" but can be used with inheritance
      4. internal
         1. The type or member can be accessed by any code in the same assembly, but not from another assembly
         2. Similar to "public" but can be accessed within the same assembly of the class
      5. protected internal
         1. The type or member can be accessed by any code in the same assembly, or by any derived class in another assembly
         2. Can be accessed within the class, subclasses, and the assembly
