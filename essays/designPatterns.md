---
layout: essay
type: essay
title: Game of Code - The Designers of Westeros
date: 2017-12-03
labels:
  - coding design patterns, factory, prototype, singleton, pub-sub, observer, gof, gang of four
---
# Game of Code
*spoiler disclosure - I am not responsible for any spoilers that I may unintentionally give away* 

I noticed that my most engaged learning happens when I combine analogy and humor. So I'm currently learning about Programming Design Patterns and the Gang of Four and all the Classic Jazz of Software Development.... and thinking of Game of Thrones of course? So I thought I would put together one of those "What GoT Character are you?!?" sets for Design Patterns and hopefully you'll be able to... 
- Learn Something New? 
- Laugh? 
- Start Watching Game of Thrones? 
- All 3? 

## What Design Pattern Are You? Game of Thrones Style

### Prototype = Arya
<img class="ui small left floated rounded image" src="http://www.newstalk.com/content/000/images/000147/151623_54_news_hub_137623_656x500.jpg">
She may be small, but she's got a lot in store for you. If this girl can't copy paste, I don't know who can. Ayra is the main contender for prototyping because all she needs is her templates/ skinned off faces to just face change into a new person. Prototyping reminded me of her because it uses classes to create these cookie cutter classic object oriented methods that can be reimplemented again for later. 

### MVC: Model - View - Control = Little Finger / Lord Baelish
<img class="ui small right floated rounded image" src="https://vignette.wikia.nocookie.net/gameofthrones/images/9/90/Petyr_s6.png/revision/latest?cb=20160828101144&path-prefix=tr">
Bum bum buuuuuum. This creeeeep is the MVP of the MVC design model. Model - View - Control is how most websites *control* a hidden database behind closed doors. There is a *model* that explains how they decide what a client can *view*. This reminded me of Little Finger because he's always trying to keep some secret plan covered up and you never really know what his motives are or how he got in the position he's in. But as for the viewers it doesn't matter because they're just trying to get back to Winterfell or whereever they need to go on a website. 

### Flow Control / Router = Varys
<img class="ui small left floated rounded image" src="https://cdn.pastemagazine.com/www/articles/VARYS-GAME-OF-THRONES-quotes.jpg">
This is the guy you need for a royal court because he's got all the connections. A flow control model helps delegate which routes should flow to where. Whether you know it or not, they've got their eyes on who is talking to who and where. Varys is like a mean girls gossip queen trapped in an eunuchs body. So he knows about all the connections and who is talking to who. 

### Observer: Pub - Sub = Tyrion
<img class="ui small right floated rounded image" src="http://i.telegraph.co.uk/multimedia/archive/03295/Tyrion_1_3295189b.jpg">
Did someone say Pub?? Tyrion is the hand of the queen for Danaerys so he's got to keep up with all of her subscribers and he publishes the news to her and them anytime something has changed or been updated. This is how one way of the Observer method works (or pub-sub). It has a publisher that handles subscriptions to the data base and it updates all of the subscribers asynchronously. 

### Observer: Reactive = Jon Snow
<img class="ui small left floated rounded image" src="https://metrouk2.files.wordpress.com/2017/03/jon-snow-game-of-thrones1.jpg?w=748&h=374&crop=1">
Jon Snow is of course the hero who is just trying to be extra and save the day when something has happened. So I thought he would be the perfect match for Reactive programming models. This is similar to pub - sub and other observer models that sort of do so for you without having to ask them to. A reactive funtion is aware of its state so that if it changes it updates whatever needs to be updated or notified. Jon Snow is like this in that, he's just waiting on his next moment to swoop in and save the day.

### Singleton = Daenerys
<img class="ui small right floated rounded image" src="http://digitalspyuk.cdnds.net/17/33/980x490/landscape-1502793837-daenerys-drogon-got.jpg">
Out of all of the analogies I feel like this one was the most perfect match. Singletons are a classic way in programming to make sure that only one instance of a program is created. In other words, all other instances must bend the knee. If you're not watching the show, Daenerys is (as far as most of Westeros knows atleast) the rightful born heir to the thrown and she's not going to backdown until all other royalty bends the knee and accepts her as queen. 

### Factory = Queen Cersei
<img class="ui small left floated rounded image" src="https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/cersei-euron-gift-1500579238.png?crop=1.00xw:0.892xh;0,0.0684xh&resize=980:*">
If there is one thing you can praise Cersei on it's running a tight ship. She's always got everything plotted and organized, never mixing business where it doesn't belong. People might be aware of all the pockets she's got her hands into, but she makes sure they don't know about all the details of one another. Factory design code acts similar to that (or more like a factory) in that it designs some units that will encapuslate and trickle down while others are just side branches doing a compeletely other set of tasks. Either way there's a factory overseeing all of the different subgroups and controlling their access to one anthother. 

### Anti-Patterns: Lava Flow = All the Kings
<img class="ui small right floated rounded image" src="http://digitalspyuk.cdnds.net/16/25/980x490/landscape-1466683466-aerys.jpg">
Quick summary: 
- Aerys     -  Mad King
- Robert B  -  Drunk
- Joffrey   -  He deserved it
- Tommen    -  yea... that was sad
<br>Not sure what's going on down there anymore, but Dany is about to show them what real lava is all about. Anti-patterns are coding design patters that just shouldn't be repeated. The Lava Flow pattern is what happens when someone leaves crappy code somewhere and no one wants to mess with it. So it just becomes this hot mess everyone is avoiding until it's been there so long that it just solidfies and no one can move it. Eventually people build on top of it and it becomes part of the foundation and pontentially a risk for the whole program to fall apart. 

## Ok back to reality....

  So in school I've had the opportunity to work with projects that implement several of these patterns. One example of this is in my software engineering class where we complete a project using the Meteor frame work. Meteor frameworks use the pub sub method to handle its updates asynchronously. This is done by storing a little database known as minimongo that is held on each client. It stores enough data necessary so that a subscriber can function asynchronously while the publisher is updating.
  This same project features serveral other design methods as well. It is a web application so the model-view-control pattern is included. The viewer side is handled mostly with the html and css files while the control handles the database. Routers are used as well in a flow control design feature that routes the buttons an client side actions to the server. Our professor even integrated a singleton and a factory (define()) method to make sure that we are getting exposure to these design patterns. Lastly, we're using javascript of course so we're exposed to the prototype model as well. 



