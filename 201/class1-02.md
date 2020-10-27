# Pre-notes


## HTML Text

white space does not matter in html, if you type a code and put any more of spaces it won't change a thing as long as that space is inbetween. this is why you would use special html bracktes to edit your text in markdown

<br /> - This will force whatever text is after to be show a line underneath before the text it was placed.

<hr /> - This allows you to add a horizontal rule and put a line inbetween elements 

<strong></strong>- This is make any text bold 
<em></em>- this will make any text italic 
<blockquote></blockquote>- used to give a whole box of space for a quote, p and other element can be used inside
<q></q>- this used to put quotes around text but most html don't do anything with this anymore
<abbr title=""></abbr> - this can be used for acronyms and will display the full text of it when hovered over
<cite></cite> - this is used to indicate citation
<ins></ins>, <del></del> - this can be used to show what been inserted or deleted


## CSS 

 Selector{Declaration: Value                                
        propert: value;  }  



### Color  

color: name/code/value;}  

background-color: name/code/value;} - This will target the element background box. Each element has an box around it  

RGB Values - This expresses colors in red, green, and blue and with the amount of each color you want used. Example: rbg(100,100,90)    

HEX CODES - six-digit codes that represent the amount of red, green and blue in a color procede by a #. Example: #ee3e80  

COLOR NAMES - Web browsers recognize 147 predefined colors names. Example: *DarkCyan*  

opacity: 0.0-1.0;} - Using a scale of 0.0 being 0% to 1.0 being 100% opacity you can change it by using the numbers inbetween the scale to make it the right opcaity you want, you can use rgba command to have the opacity value inside the color as well.                     Example: rgba(100,100,90,0.5);}  

hsl, hsla - These are another color property, h stands for **HUE** which is express in a 0 to 360 angle degrees. s stands for **SATURATION** which is expressed as a percentage 0-100%. l stands for **LIGHTNESS** which is expressed with 0% being white, 50% being normal, 100% being black.  

hsla - is the same thing but with the a stands for **ALPHA** just like in rgba its vaulue is for transpearency expressed in 0.0-1.0


## JavaScript

JS is the muscle for the page, this is what allows the page to be functional. It can store variables, iterate through arrays. It act more like a programming language. 

Variables =  this temporary storage of something

var name = 'Roger'

name = 'Stacy'
console.log(name + ' is your instructor');

Stacy is your instructor 


### Objects and Methods

**document.write('Good Afternoon!')**

The above is a line in JavaScript and hows how to use objest and methods. 

**document** - this is the object on the line.
**.** - this is the member operator, helps find methods and properties of the object beforehand
**write** - this the method/ or could be a property as well if chosen
**('Text')** - this is the parameter, methods need information in this field in order to work

<script></script> - When a browser comes across a script, it stops and loads the script and then checks if it needs to do anything. Scripts will come out on the page wherever you place it in the html file. Scripts can also affect loading times for pages.  
What is a variable?
A variable is a container that holds a piece of information  

Example: var userName = promt('What is your name?');


### Datatypes

- **string** = 'text', or ""text"" 
- **number** = 45, 23 , 11 ,2 , any number 
- **=,==,==** = is an assignment operator, == is an equal, === is an strict equal. Good practice is using the triple equal, double equal can lead to injections   
- **Boolean** - this can either be true or false. 1 or 0

### Operators  

**==** - Is equal to  
**!=** - is not equal to  
warining, try not to use the two above, not safe or best practice.  
**===**-strict equal to  
**!==**-Strick not equal to  
Always better to use strick equals operators!  
**>**-greater than operator  
**<**- Less than operator  
**>=**- greater than or equalt to operator  
**<=**- less than or equal to operator  

## Logical Operators  

**&&**- Logical and, this test more than one condition. Both condition must be true for it to return ture  
**||**- Logical or, this test at least one condition. Either expression can be true or false and will return in true, but if both are false, it will return false.  
**!**- Logical not, this takes a single boolean value and inverts it. It makes whatever you put ! infront reverse. Example !true returns false. !false returns true  

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


## Class Note

root|
    | index.html
    | README.md
    |.eslintrc                            - the dot make the files hidden
    |.gitignore                           - this will not push any files in here
    |_____________ css
                   |reset.css
                   |styles.css
    |
    |______________js
    |              |app.js
    |              |
    | 
    |





[<== Back](../README.md)