---
layout: project
type: project
image: images/printer_small.jpeg
title: GPri - Liquid Metal Printer
permalink: projects/printer
date: 2017
labels:
  - Matlab
  - Liquid Metal
  - Galinstan
  - Gcode
  - Material Science
  - Graphene
  - Flexible Electronics
  - Flexible Devices
summary: The making of a liquid metal printer. 
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/printer_big.JPG">
  <img class="ui image" src="../images/printer_logo.JPG">
  <img class="ui image" src="../images/priter_metal.JPG">
  <img class="ui image" src="../images/printer_diagram.png">
</div>

<ul>
  <li> Designed and constructed a galinstan (liquid metal) deposition system for automated graphene transistor prototyping, which enables smaller feature sizes and improved device performance </li>
  <li> Synchronize 3 staged linear actuators with a microfluidic control system by creating a MATLAB interface from provided software development kits </li>
<li> Investigate the physical properties of liquid metal and the effect those properties have for automated fluid deposition </li>
</ul>

## Background
The GPri is a result of my Summer internship of 2017 at SSCPAC (SPAWAR Systems Center Pacific). I was invited to work the Graphene Microfluidics Laboratory (GML). When I arrived the GML team had already passed their proof of concept phase by creating a graphene transistor. Their goal during this Summer was to miniturize their devices and my project was an effort to automate that process. Thus, the inspiration for the GPri (Galinstan Printer) was drafted. 

So what is <b>Galinstan</b>? Galinstan is one of the compounds known casually as "liquid metal". It is a portmateau of its chemical components: Gal-In-Stan = Gallium, Indium, Tin (Stannum). Liquid metals are alloys that are liquid at room temperature. The Graphene Microfluidics Lab found interest in liquid metal for its potential use in flexible electronics. It also provides a more reliable contact for the source and drain of transistors, as opposed to rigid metals. 

### My overall goal for this project was to assemble, test & prototype a research instrument that deposits Galinstan with high precision accuracy (in the 10^1 microns range). 

This instrument would perform the same way that an ink jet printer would, except with liquid metal. In order to achieve a *miniaturized graphene device*, the liquid metal channels (or printed lines in essence) would ideally be around 50 microns in width. 

## Parts
THOR LABS DRV-014 Linear Actuators + BSC203 Control Unit
<ul>
  <li><b> THOR LABS DRV-014 Linear Actuators + BSC203 Control Unit </b></li>
  <ul>
    <li> 409,600 µSteps / 50 mm  </li>
    <li> Less than 1 µm bidirectional repeatability </li>
    <li> Up to 50 nm resolution </li>
  </ul>   

  <li><b> Fluigent (MFCS-EZ) Pneumatic Pressure Control System </b></li>
  <ul>
    <li> Specifications are Specific to the Solution... No references for Liquid Metal </li>
  </ul>
</ul>


## Software
DRV-014 with the BSC 203
ActiveX Platform- Microsoft Component Object Model (COM) 
Binary Interface between OS & program
Utilized through control containers 
Matlab = client
ActiveX control = server
Accessible methods, properties and events

MFCS-EZ
Microsoft Dynamic Link Library (DLL)
C calling convention 
Responsible for cleaning the stack
Function Handles - ptr to funct.



