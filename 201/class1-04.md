# Pre-Notes

## HTML

### Links

```<a href="link goes here">text user clicks goes here</a>```

this is how you make a link in html

### directory structure

    It goes from parent to child, grandparent to grand child

Essentially linking in the same folder only requires the file name.

child folder will required a parent/child link
grand child wil require grandparent/parent/child to link

parent foler requires a ../parent to link from a child

and for grand parent all you need is ../../grandpent to link from granchild

mailto: - this will make the link automatically open an email program and set up to specified email
```<a href="mailto:emailgoeshere!">text goes here</a>```

target="_black" - this will open a new window with specified link
```<a href="url go here" target="_blank">```

you can select an element in the page to link to by using an id selector

```<a href="#id">text goes here</a>```


## CSS

### Layout

css treats every element as its own box, it will go as an block-level box or an inline box

block-level elements
```<h1><p><ul><li>```
inline-elements
```<img><b><i>```

Highly recommend you make a div element to group up elements that go usually in one area.

using the z-iden:10;
property we can till what blocks go above others in css, with the higher index going above 

using float: right; or left; will make the element go as far right or left and making anything else sitting in the elemnt flow around the element that is floated

clear: left; right; both; none; -- this can help control boxes selected by the same type in a float so that the boxes can't touch other left or right sides of a box

using the overflow:auto; and width:100%; can help with a parents of floated elements problem

