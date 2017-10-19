---
layout: essay
type: essay
title: Meteor Gotchas
date: 2017-10-19
labels:
  - software engineering, meteor
---



# What's got me in Meteor
<br> 
<img class="ui medium left floated rounded image" src="https://www.anychart.com/_design/img/upload/plugins/meteor-logo.png">
     In my software engineering course we've been going over this new JS web framework called meteor. Meteor is cool because it uses pub / sub so you don't have to have the user refresh all the time. We've been using the Mongo Database with this as well. From what I've gathered, you get this little *mini-mongo* database that sits on the client side of the browser. This will help the user update the dynamic data fluidly. The meteor app will consistently check to see whether or not the mini-mongo database matches up with the database on the home server. 

<br>
     So far we're about 1/2 way through the learning experience of tutorials with Meteor. Where I have struggled the most so far is with Meteor's default templating system. It was really difficult to know what was a variable coming in, what was going out, and where it came from or was heading to. I honestly wish there was some sort of editor feature that would highlight an instance, and have like a dropdown for all the file locations that something is metioned. After doing our tutorials a couple times though, I became more familiar with how the templates route through the helper functions and how to set them up correctly. 

<br>
    Another problem I've had was one that our professor already warned us about. I keep forgetting to make sure that everything is set up for my pages in the backend. For example, if I make a page, I need to make sure that it's instantied in the router file. Otherwise all of my time invested work will load to nothing. 

<br>
    My best advice for the newbie who is trying to figure out Meteor is to just do a guided tutorial. Let go of your courage and pride and forget that you have any experience in programming. When you go through a guided tutorial step-by-step you have the certainty that you're doing everything correctly and you're able to check yourself periodically. This helps so much in debugging, because you'll know the last place where you had everything working correctly and if you have to scrap anything, at least you won't have to start from scratch. 


