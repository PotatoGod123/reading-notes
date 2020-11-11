# Pre-notes

## JavaScript


### localStorage

HTML5 storage is based on named key/value pairs, just like javascript. you store the data on a based named key then you can get it back with the same key.  

```JavaScript
interface Storage {
  getter any getItem(in DOMString key);
  setter creator void setItem(in DOMString key, in any data);
};
```  

Remember you can store anything data into the localStorage but they will turn into a string whenever you try to retrieve them, so you must turn them into your value you need them to be.

[<==Back](../README.md)