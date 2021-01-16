# Javascript

## EJS


Use **npm init -y** then do**npm install body-parser ejs** in the terminal to install these dependecies. Then declared and require said dependecies in your server.js. Remember to set up a path dependecy as well since its comes a pre module for node. Which takes two paths and joins them.  


```Javascript 
app.set('views', path.join(__dirname,'views'));
```


this will concatenate whatever view engine and the current directory file.



```Javascript
<%= var%>
```

This will evaluate a var for you, when you use it in render. so you can pass anything. Kinda like mustache.


```Javascript
<%= for(var varName of key) {>

    varName.key;
<%=}>
```  

A for loop