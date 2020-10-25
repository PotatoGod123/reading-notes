# Pre-notes  

## HTML  

What does HTML stand for?  

    - Hypertext Markup Language  

index.html - This is standard file type for websites  

## Information  

    - Used in conjuction with css and javascript to provide a fully flesh website and allows you to create sturcture for paragraphs and headings

## Process & Design  

    - It's important to understand who your target audience is, why they would come to your site, what information they want to find and when they are likely to return and how often they do
    - Site maps allow you to plan the structure of a site
    - Wireframes allow you to organize the information that will need to go on each page
    -  Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them.
    - You can differentiate between pieces of information using size, color, and style.
    - You can use grouping(how they are sorted and put together) and similarity(what size,font, color and style that have in comon) to help simplify the information.

Website first to go up is HTML = Foundations  
Add CSS to make the site look good = Structure  
JS - makes the site functional = Internal Functions  

## Tags  

    - <html> <!DOCTYPE html>
    - <p></p>
    - <body></body>
    - <header></header>
    - <h1><h2><h3><h4><h5><h6></h#>
    - <img src="" />  >> <img srch="" alt="" />
    - <nav></nav>
    - <ul></ul>  >>  <li></li>
    - <footer></footer>
    - <aside></aside>
    - <article></article>
    - <section></section>
    - <figure></figure>  >> <figcaption></figcaption>
    - <div></div> , to group outside elements
    - <iframe width="" height="" src=""></iframe> Essentially it cut a smaller frame in line that is usually used with src=""
    - <iframe></iframe> frameborder"" scrolling="" for old html , seamless for html5
    -<meta/> Use for website specific informations to be given to web search engines and actions for the broswer to do/search engines. Usually found in the header by the title
    - <!-- --> , this is to make comments. MAKE SURE TO COMMENT!! can be also used to hide out elements in code
    - id="" , example: <p id="example"> Meme </p> , this gives any element it's own unique identifacation, if same name is used on another id its it no longer unique so don't do it! use a class
    - class="" , example:<p class="example">test</p> , you can use a class to set apart different elements togother. Usually to make the same elements different from others of the same element
    - <span></span> , Use inline to usually class or id an element that you want to be used differently in css, example: <span class="example">test</span>
    - To make the website work on older browsers, you need extra javascript code which is on google for free

# Javascript

## Scripts

A script is a series of instructions that the computer can follow in order to achieve a goal. When a script is run it might only use a subset of all the instructions. The instructions must let the computer solve the task programmatically. Using a flowchat can help greatly in writing as it will allow you to break down the goal into a series of task and then work out each step needed to complete the task  

## Expressions

Expression results in a single value. Broadly speaking there are two types of expressions

Expressions that just assign a value to a variable
 var color = 'beige';
The value of color is now beige

Expressions that use two or more values to return a single value
    var area = 3 * 2;  
The value of area is 6

## FUNCTIONS

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
