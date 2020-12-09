# Javascript  

## Jquery  


```Javascript
$('li.hot').addClass('complete');
```

The above is an example of jquery being used, you can use jQuery() function to select anything in the DOM with css selectors but people use the shorthand $ to use the function. Remember to link jQuery into your html above the script you are using the funcntion in so that they have a reference point.  

[jQuerywebsite](http://jquery.org)  


```Javascript
$cathingDOM = $('Node');
```

This is to cache something from the dom so you don't have to repeat it.

**Looping** is made easier is you select all of the element you want to change in the selector parameter. Like  
```Javascript
$('li.hot').addClass('favorite');
```
The above will add the class favorite to every li element with the hot class. 

You can also **chain** methods on the selected node by using . after each method, to make it redeable place each method on a new line. Remember if one method fails the ones underneath will not run.  


```Javascript
$(document).ready(function(){
  //put your script here
});
```  

The above is a method to be used only when the DOM of the page is fully loaded. here is the shorthand method  

```Javascript
$(function(){
  //script hoes here
});
```  

```Javascript
.html()//this will get the selected first matched element and its child and return the entire html code Ex:$('ul').html(); returns <li>1</li> <li>2</li>
.text()// this will only return the text from the selected element, 
```



# Pair Programming

Doing pair progamming is extremly useful, one it helps relieve stress of making errorss when typing code and leads to cleaner typing as well while also focusing on the task at hand and learn from each others as the programming progresses.  


[<==Back](../README.md)