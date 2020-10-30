# Pre-notes


## HTML

### Images

Images should be

- Relavent
- Convey Information
- Convey the right mood
- Be instantly recognisable
- Fit the color pallete

- ```<img src="" />  >> <img srch="" alt="" />```

Save images in the right format and the size you want them to be on your website, smaller image with bigger width and heigh values will strech out the image  and look blurry while larger images will take longer to load in the site

Remember! measure images in pixels! Use photo ediditng software to make changes to images. Use .jpeg for images with lots of colors and patterns, use .png for images with simple amount of colors and basic designs. Vector are special cause they contain their quality no matter what size you change it too
A figure element can be used to contain the image and a caption in it as well

```<figure>img here</figure>```
```<figcaption>caption of image here</figcaption>``` - this goes inside the figure element to represent the caption that goes inside


## CSS

### Color

color: name/code/value;}  

background-color: name/code/value;} - This will target the element background box. Each element has an box around it  

RGB Values - This expresses colors in red, green, and blue and with the amount of each color you want used. Example: rbg(100,100,90)    

HEX CODES - six-digit codes that represent the amount of red, green and blue in a color procede by a #. Example: #ee3e80  

COLOR NAMES - Web browsers recognize 147 predefined colors names. Example: *DarkCyan*  

opacity: 0.0-1.0;} - Using a scale of 0.0 being 0% to 1.0 being 100% opacity you can change it by using the numbers inbetween the scale to make it the right opcaity you want, you can use rgba command to have the opacity value inside the color as well.                     Example: rgba(100,100,90,0.5);}  

hsl, hsla - These are another color property, h stands for **HUE** which is express in a 0 to 360 angle degrees. s stands for **SATURATION** which is expressed as a percentage 0-100%. l stands for **LIGHTNESS** which is expressed with 0% being white, 50% being normal, 100% being black.  

hsla - is the same thing but with the a stands for **ALPHA** just like in rgba its vaulue is for transpearency expressed in 0.0-1.0.  



[<==Back](../README.md)