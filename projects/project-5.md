---
layout: project
type: project
image: images/comicon_glasses.png
title: Electric Storm: Cosplay meets Tech
permalink: projects/comiccon
date: 2016
labels:
  - Arduino
  - C++
  - Wearables
  - Cosplay
summary: Wearable Electronics for a costume featured in a talk at the Amazing Hawaii Comic Con 2015
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/comicon_glasses.jpg">
  <img class="ui image" src="../images/comicon_presentation.jpeg">
</div>

Teams compete to simulate a Mars payload descending and taking atmospheric measurements to be submitted to a ground station. 

CanSat is a NASA sponsored event in which teams worldwide compete to simulate a Mars payload descending and recording and transmitting atmospheric measurements to be submitted to a ground station. The focus of this competition is to recreate the engineering research and design process that makes a Mars payload project possible. There are several design limitations that each team must meet in order to compete. The payload's design is restricted by a number of factors such as limits on mass, flight path, cost, and durability. These factors heavily influence the electronics that may be used for data collection based on the size, power, and communication limitations. Aside from constructing the payload, aach team must present several preliminary designs to a NASA engineer for review before the payload launch in Texas. 

During this project, I was primarily responsible for the flight logic and designing the release mechanism using nichrome wire. 

Micromouse is an event where small robot “mice” solve a 16 x 16 maze.  Events are held worldwide.  The maze is made up of a 16 by 16 gird of cells, each 180 mm square with walls 50 mm high.  The mice are completely autonomous robots that must find their way from a predetermined starting position to the central area of the maze unaided.  The mouse will need to keep track of where it is, discover walls as it explores, map out the maze and detect when it has reached the center.  having reached the center, the mouse will typically perform additional searches of the maze until it has found the most optimal route from the start to the center.  Once the most optimal route has been determined, the mouse will run that route in the shortest possible time.

For this project, I was the lead programmer who was responsible for programming the various capabilities of the mouse.  I started by programming the basics, such as sensor polling and motor actuation using interrupts.  From there, I then programmed the basic PD controls for the motors of the mouse.  The PD control the drive so that the mouse would stay centered while traversing the maze and keep the mouse driving straight.  I also programmed basic algorithms used to solve the maze such as a right wall hugger and a left wall hugger algorithm.  From there I worked on a flood-fill algorithm to help the mouse track where it is in the maze, and to map the route it takes.  We finished with the fastest mouse who finished the maze within our college.

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).



