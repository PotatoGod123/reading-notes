# Responsive vs. Adaptive vs Mobile

Responively meant to ract quickly and positively to any change, essentially it changes whatever is on the screen to customily fit the viewport/window the page is being view on, adaptive on the other is to make the web able to be easily modified for a new purpose or situation, such as change. Good design is combining both of these to make a fluid website. Mobile is making an entire new webpage specifically with phgones in mind, this really isn't pratical but do have it uses here and there.  

At the moment, the most popular techniqwue in responsive web design, is using all three so that it dynamically adapts to different browser and device viewwports, while changing content layout along the way.  

Responsive web design is broken down into three main components, including flexible layouts, media queries, and flexible media.  

## Flexible Layouts  

This part is a pratice of building the layout of a website with a flexible grid, capapble of dynamically being resized to any width. This done with relative length units, em or percentages. For this reason using pixels or inches are not advice, use this formula to make into a relative value  

**target ÷ context = result**  

ex. the max width of the container is 538px with the margin of the content inside being 10  

10 / 538 = .018587361 , which is 1.858736059%.  using .018587361em is fine as well  

## Media Queries  

Using the **@media** rule inside of an existing style sheet, importing a new style sheet using the @import rule, or by linking to a separate style sheet from within the HTML document, it's best to use the @media rule inside an existing style sheet.  

Each media query may include a media type followed by one or more expressions. Common media types include **all, screen, print, tv, and braille**.  Should a type not be specified it will be set to screen.  

different logical operators available for use within media queries, including **and, not, and only**. Commas **,** are used as the unspoke or operator

using these and (min/max-width/height) you are able to make special css rules that run with the targerted media and apply changes for a dynamic viewing experiences  


Using mobile first technique allows your to efficiently use the users data wisely by having to load less and take less bandwidth while they browse their site on there phone. After which you increase your site layout as the higher the min-width of the screen is being used.  

``` html
<meta name="viewport" content="width=device-width"> 
```  

This is commonly used to the the mobile device to use it's own man height and width for it's screen when recieving the website on the mobile browser.  

[use this link for more info](https://learn.shayhowe.com/advanced-html-css/responsive-web-design/#flexible-layouts)  


## CSS FLOATS  

Four valid values for the float property. Left and Right float elements those directions respectively. None (the default) ensures the element will not float and Inherit which will assume the float value from that elements parent element.  

Using flexbox and grid was way stronger toals but float still has it's own unique uses.  

Using the float clear property allows an element to move itself past down the float of other elements.

As float clear has for valid values **Both, Left, Right, None, Inherit**

Essentially using float extremely intensively becomes a pain in the ass and good luck :)


[use this link for picture of examepls](https://css-tricks.com/all-about-floats/)


[<==Back](../README.md)