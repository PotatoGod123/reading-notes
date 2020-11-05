# Pre-Notes

## HTML

### Forms

Whenever you want to collect information from visitors you will need a form, which lives inside a ```<form></form>``` element. Information from a form is sent in name/value pairs. Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server. HTML5 introduces new form elements which make it easier for visitors to fill in forms.

### Events

Events are FIRED or TRIGGERED event types:
`*` page load, error, resize
`*` kepup, hover, click, mouse up


LISTENER = code that is waiting for an event  
HANDLER = code that takes action when an even is fired  
BIND = an event to an element in three ways
1.```<div onSubmit="hanldeEvent()">``` this old way, don't do this  
2.```element.onevent = eventHandler()``` old as well, dont do  
3.``` element.addEventListener('event', functionName);``` do this, modern  

ASYNCHRONOUS CODE - code that runs out of order  
CALLBACK function - a function that is an arguament to another function

By default, an event listener will hear everything in its children element



function bananas(event){
  event.preventDefault();

  //console.log(event.target.username.value);
  var personName = even.target.username.value;
  var story = even.targer.story.value
  var likesIcream= event.target.icecream.value;

}

formElement.addEventListner('submit',bananas);

[<==Back](../README.md)
