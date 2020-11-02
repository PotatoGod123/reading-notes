# Pre-Notes

## JS

### Object Literals

A object groups of variables and functions together to resemble something to be use in real life. If a **variable** is in an **object** it becomes know as a **Property** , while if a function is in an **object** it become knowed as a **method**. Property's and methods have names which are called **keys**, In a object there cannot be two **keys** with the same name because is each key is used to access there corresponding values. **Values** of the property can be a string,number,boolean,array or even another **object**. The value of a method can only be a function. 


```var hotel ={```
```name: 'Quay',```
```rooms: 40,```             these are properties, each key ends with a colon: and each property is seperated with a comma the same with a method
```booked: 25,```
``` ```
```checkAvailabilty: function(){```
```return this.rooms - this.booked;```         this is a method, as you can see it's using the **this.** to specify using that specific obejects keys 
```}```
```};```

to call the object and it's key and values you use this command

```var hotelName = hotel.name;``` **hotel** is the object that was made, name is the property
```var roomsFree = hotel.checkAvailability();``` this calls the method instead by putting the name of the method in the scone part

the **.** is called the member operator
you can also call them with this

```var hotelName = hotel['name'];```
```var roomsFree = hotel['checkAvailability']();```


### DOM

The browser represents the page using a DOM tree. DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes. You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax. Whenever a DOM query can return more than one node, it will always return a NodeList. From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques 


```document.getElementById(id)``` 	Find an element by element id
```document.getElementsByTagName(name)``` 	Find elements by tag name
```document.getElementsByClassName(name)``` 	Find elements by class name


[<==Back](../README.md)