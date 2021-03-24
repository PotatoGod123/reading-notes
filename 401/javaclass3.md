# Java  

## Primitives vs.Objects 
Java has a two-fold type system consisting of primitives such as int, boolean and reference types such as Integer, Boolean. Every primitive type corresponds to a reference type. Every object contains a single value of the corresponding primitive type. Which the wrapper class are immutable.

- boolean – 1 bit  
- byte – 8 bits  
- short, char – 16 bits  
- int, float – 32 bits  
- long, double – 64 bits  

In short, using primites over than wrapped objects is usually better since they use and require less memory to run, improving perfomance.


## Exceptions In Java

An exception is an event, which occurs during the execution of a program, that disrupts the normal flow of the program's instructions. Essentially when an erros happend an object is get made with all the details and thrown to bet catch by something, usually the compiler.  
 
Valid Java programming language code must honor the Catch or Specify Requirement. This means that code that might throw certain exceptions must be enclosed by either of the following:  

- A try statement that catches the exception. The try must provide a handler for the exception.  
- A method that specifies that it can throw the exception. The method must provide a throws clause that lists the exception  

Runtime exceptions are not subject to the Catch or Specify Requirement. Runtime exceptions are those indicated by RuntimeException and its subclasses.

Errors and runtime exceptions are collectively known as unchecked exceptions. Usually its not recommened  to catch and specify requirement to be a flaw instead of using checked exceptions.

## Scanning files in Java

Objects of type Scanner

Gives access to new Scanner object which in turn gives access to method to be used when reading files.

[<==Back](../README.md)  
