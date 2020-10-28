# Pre-notes

## List

In HTML there are three different types of list  

- Ordered list are list where each item in the list is numbered.  

<ol><li></li></ol> 


- Unordered list are list that begin with a bullet point

```<ul><li></li></ul>```

- Definition list are made up of a set of terms along with definitions for each of those terms

```<dl></dl> - This will make a definition list```
```<dt></dt> - this is to contain the term being define```
```<dd></dd> - this is to contain the definition of the term```

You can nest a list inside another list


## Boxes

In css you can change how the boxes and size of boxers of HTML elements

width: 10px 10% or 1.0; - This will set the width of the box
height: 10px % or 1.0 ; - This will set the height of the box
min-width: 10px 10% or 1.0; - This and the property below help set a limit to the design you are trying to do smaller web browsers  
max-width: 10px 10% or 1.0; 
min-height:10px 10% or 1.0;
max-height:10px 10% or 1.0;

```overflow: hidden/scroll;```  - this property well either hide all overflowing text from the box size or make it into a scroll for the person to see the rest

Border, Margin, and Padding are the three things in a box you can edit with css.

Both margin and padding can help keep text from touching the border

border-width can be used to control the width of a border

border-width:thin,medium,thick, 10px;

you can also control the width of one side with

border-top-width
border-right-width
border-left-width
border-bottom-width

border-style will control the style of the border

solid
dotted
groove
ridge
inset
outset
hidden/none 

these can also be used with 
border-top-style
border-lefy-style
border-right-style
border-bottom-style


same with color 
```border-color: top right bottom left```

padding allows control between the space of the content and the box it self

padding-top
padding-right
padding-bottom
padding-left 

Short hand version
```padding:top right bottom left;```

### Margin

This controls the gap between boxes, allows you to position in the place you want them to show in the page

margin-top
margin-right
margin-bottom
margin-left

Short hand version
margin: top right bottom left

```margin: 10px auto 10px auto;```   - This will align the box to be right in the center of the page

### Display

```display: ;```

inline - this will cause a block-level element to act as an inline element 

block- this will make an inline element into a block-level element

inline-block  - this cause a block-level element to act like an inline element while still retaining the other feature of an block element

none- this hides the elemnt from view

### Visibilty 

```visibility: ;``` - this allows you to hide boxes from users but it leaves a space where the lement would have been

hidden - hides the element but shows a black space

### border-image

```border-image: url() 11 11 11 11 strech,repeat,round;```

```box-shadow: -5px -5px #777777;```

positive and negative values well affect where it shows up

### border-radius

```border-radius: ;``` - this will round out the box or curve it depending what value you put in

[Cheat Sheet for css](https://overapi.com/css)

## JAVASCRIPT


### Arrays

Arrays isn't just a regular varuable, it's a variable that can hold multiples values


```var colors;``` 
```colors = [ 'white','black','custom'];```

Each items in an array is automatically given an index[0] and keep ascending from there upwards starting with 0.

index   value
0       white
1       black
2       custom

```var colorChooser;```
```colorChooser = colors[2]; ```
```the output for this will be custom ```

```var colorNumber;```
```colorNumber = color.length;```

this will set colorNumber to be the numbers of items in the array  


 ### Switches  

```var msg;```
  ```var level = 2;```

   ```switch(level){```

     case 1:
           msg ='Good Luck on first';
           break;
     case 2:
           msg =' Good luck on second';
           break;
     case 3:
           msg ='Good luck on third';
     deafult:
           msg='Good luck';
           break;
``` }```

 ### Loops  

**for (var i=0; i<10; i++) {**
    **documment.write(i);**
**}**  

**for**- The keyword  
**(var i=0; i<10; i++)**- The condition(counter)  
    - **var i=0;**- this is the initialization, sometimes you'll see it be made right before the loops is made  
    - **i < 0**- this is the condition  
    -**i++**- Update, Every time the loop runs the statement in the curly brackets it will add one to the counter  
**{documment.write(i);}**- code to execute during loop  

The above is an example and a common loop. you can use three keywords for a loop  
    - **for**- Use this keyword if you need run a loop a certain amount of times since you can tell it to run how many times you need it to run.  
    - **while**- If you do not know how many times it needs to run, use this keyword for a loop and it will keep looping till as long the condition is true.  
    - **do while**- This is similar to while but it will run whatever is in the codeblock at least once even if the condition comes out false.  

**+=** - Allows you to add the statement from it's past loops  




[<==Back](../README.md)
