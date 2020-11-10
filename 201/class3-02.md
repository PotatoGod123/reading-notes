# Pre-Notes

## CHART.JS

Essentially CHART.JS is a javascript plugin that will use the HTML5 canvas element to draw the grpah onto the page. Allows you to draw good looking charts from bar,line,pie,and more.
To use you must first [download](https://github.com/nnnick/Chart.js) then copy the chart.min.js out of the unzzippled folder into the directory you are working in.  Use this [link](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/) or [link](https://www.chartjs.org/docs/latest/) to learn more. 


Remember to use fall back content, if a brower does not support canvas it is better to tell use fallback than just telling to user to swap browsers.

```JavaScript
var canvas = document.getElementById('tutorial');
var ctx = canvas.getContext('2d');
```  

Ctx can be set to either 2d or 3d, use other tutorials for 3d.  Always check for support on web browsers!!! run an if command to check if it does work. 

Remember that canvas element works are a grid when drawing or putting anything on it. 1 grid square is 1 pixel on screen. So mind how much width and height you give your canvas element.  

<canvas> only supports two primitive shapes: rectangles and paths (lists of points connected by lines).

Use links for extra resources into delving to create more advance shaps and commands.

[<canvas>](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)  
[drawing Rectangles](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)  
[Drawing text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)  
[Colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)  

[<==Back](../README.md)
