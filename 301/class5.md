# Terminal

## Heroku  

Essentially using git and heroku it seems to be able to deploy a live site of whatever repo you are in while also being able to see the logs of what happens to said site when it goes live , node essentially

These are commands to get started or follow this tutorial for basics[link](https://devcenter.heroku.com/articles/getting-started-with-nodejs#introduction) 

To start have an account with heroku and have node.js and npm instanlled in your machine and git as well.

```Javascript

sudo snap install heroku --classic//to install heroku
//then run this to login
heroku login

// once that is finish run these commands to make sure you have the nesecaser thing to use heroku
node --version
npm --version
git --version  

//now get your repo ready and cd into, 
//now type thise to create a heroku branch from your repo
heroku create//When you create an app, a git remote (called heroku) is also created and associated with your local git repository.

//now push to deploy your code
git push heroku main

//now make sure one instance of the app is running with this
heroku ps:scale web=1

//after that type this to open the new url of your repoi
heroku open
// use this to look at your logs
heroku logs --tail// updates in realtime as well

```  

[<==Back](../README.md)
