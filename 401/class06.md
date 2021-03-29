# Java  

Objects is just way of seeing things that relate in the real world and applying them to programming as well. The state of the said object, and the behavior of the object.  

An object stores its state in fields (variables in some programming languages) and exposes its behavior through methods (functions in some programming languages). Methods operate on an object's internal state and serve as the primary mechanism for object-to-object communication. Hiding internal state and requiring all interaction to be performed through an object's methods is known as data encapsulation — a fundamental principle of object-oriented programming.  


Class are esentially just how you would make something
In object-oriented terms, we say that your thing is an instance of the class of objects known as that things. A class is the blueprint from which individual objects are created.  

When different kind of objects have a certain ammount in common with each other you would use a subclass which you delcare with extends with the former class. This makes code for your subclasses easy to read. However, you must take care to properly document the state and behavior that each superclass defines, since that code will not appear in the source file of each subclass.  

A package is eseentially a library of class since anyone can make them, they are a lot of class that exist, so if you want to use one all you have to do is import the package and initilize a instance of the class.  

## Interfaces  
There are a number of situations in software engineering when it is important for disparate groups of programmers to agree to a "contract" that spells out how their software interacts. Each group should be able to write their code without any knowledge of how the other group's code is written. Generally speaking, interfaces are such contracts.  

In the Java programming language, an interface is a reference type, similar to a class, that can contain only constants, method signatures, default methods, static methods, and nested types. Method bodies exist only for default methods and static methods. Interfaces cannot be instantiated—they can only be implemented by classes or extended by other interfaces. Extension is discussed later in this lesson. 
Note that the method signatures have no braces and are terminated with a semicolon.

To use an interface, you write a class that implements the interface. When an instantiable class implements an interface, it provides a method body for each of the methods declared in the interface.

Interface being used as an industry standard Application Programming Interface (API). Essentially people will make methods and sell them to other for them to call upon them and use them in  their own works.  

## Inheritance  

What You Can Do in a Subclass

A subclass inherits all of the public and protected members of its parent, no matter what package the subclass is in. If the subclass is in the same package as its parent, it also inherits the package-private members of the parent. You can use the inherited members as is, replace them, hide them, or supplement them with new members:

    The inherited fields can be used directly, just like any other fields.
    You can declare a field in the subclass with the same name as the one in the superclass, thus hiding it (not recommended).
    You can declare new fields in the subclass that are not in the superclass.
    The inherited methods can be used directly as they are.
    You can write a new instance method in the subclass that has the same signature as the one in the superclass, thus overriding it.
    You can write a new static method in the subclass that has the same signature as the one in the superclass, thus hiding it.
    You can declare new methods in the subclass that are not in the superclass.
    You can write a subclass constructor that invokes the constructor of the superclass, either implicitly or by using the keyword super.
