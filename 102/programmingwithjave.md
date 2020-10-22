# Scripts

A script is a series of instructions that the computer can follow in order to achieve a goal. When a script is run it might only use a subset of all the instructions. The instructions must let the computer solve the task programmatically. Using a flowchat can help greatly in writing as it will allow you to break down the goal into a series of task and then work out each step needed to complete the task  

# Expressions

Expression results in a single value. Broadly speaking there are two types of expressions

Expressions that just assign a value to a variable
 var color = 'beige';
The value of color is now beige

Expressions that use two or more values to return a single value
    var area = 3 * 2;  
The value of area is 6


# FUNCTIONS

Functions let you group a series of statements together to perform  a specific task. If different parts of a script repeat the same task, you can reuse the function(rather than repating the same set of statements)

**function sayHello() {**
    **document.write('Hello!');**
**}**

**function**- this is the function keyword
**sayHello**- this is the function name, sometimes called the identifier
**{}**- this is where the code goes and is called the code block. Always in curly braces

To call on this function you would simply type
**sayHello();**
this is know as calling the function

Sometimes the function needs information for the code block inside to work. You specify the information the parameters

function getArea(width, height) {
    return width * height;
}

For the information, you can used declaration like the example above. this is called a parameter.
Or you can just specify real data like numbers.This would be an argument  

[<== Back](../README.md)