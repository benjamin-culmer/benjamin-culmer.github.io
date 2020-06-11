---
layout: default
title:  Chronometer
date:   2020-06-09 12:00:00
logo: /assets/img/clock.png
logo_options: width="400px"
tags: [project]
published: true
---

## Highlights
- Designed a complete working marine chronometer in xDesign (CAD) made entirely of group designed parts
- 3D printed the marine chronometer using PLA, achieving ±1 second precision over 10 seconds
- Voted group leader: Communicated with TAs, divided work, assigned tasks, troubleshot issues, and managed overall assembly
- Created the overall design of the chronometer, building a modular aesthetically pleasing displayable product
- Earned an award for designing a chronometer with the “most risky, cutting edge, and out of the box design innovations”

Video Demonstration of our Marine Chronometer Made by Group Member Juan Miche Rosales
<iframe width="560" height="315" src="https://www.youtube.com/embed/WmkQ7Sj34JA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Overview
For my final term, I took a graduate course where I was part of a group of five engineers tasked with designing and building
a marine chronometer made entirely from parts we designed and made. Dartmouth College provided all of us with a 3D printer and access to 3DExperience, a
web based CAD service. The goal of the competition was to build a working chronometer capable of running for at least 10 seconds achieving ±1 second precision. Our group achieved this specification and had a maximum run time of 3 minutes.
The clocks were then tested for their ability to cope with the seas by running on the print 
bed of our 3D printers with gcode written by the instructors to sway the chronometer back and forth. They were tested for
how long they could run on the bed as well as their precision during the run. Data was acquired via an arduino and encoder 
(a device sending a signal via the arduino every time its light source is uncovered). We were able to tune our clock using 
this encoder, designing a wheel would uncover the light source ever second). In the end our group received an award
for designing a chronometer with the “most risky, cutting edge, and out of the box design innovations”.


Final Marine Chronometer On Test Setup
{: style="text-align: center;"}
![clock](/assets/img/clock.png){:height="40%" width="40%"}
{: style="text-align: center;"}

## My Work
From the start, I was voted my groups team leader. As a result, I was in charge of communication with the TAs,
work delegation, troubleshooting clock issues, and managing the overall assembly. Our overall design focused on modularity
and simplicity; all parts were either press fit or snapped together through proper tolerancing. We wanted our clock as modular as possible allowing the sub-assemblies made by different people to be easily combined in the final fabrication.
The final design was unique in that all modules were concentric and stacked one above each other with a single input and
a single output between each module. The innovation coming from the methods of translating motion across the entire design. 
Because modules could only interact with those above and below, their order was crucial. I created the ordering of our complete assembly, allowing each module run only off the modules directly connected to it. This allowed us to create an 
aesthetically pleasing clock that was compact and easily displayable.

Escapement Module
{: style="text-align: center;"}
![Escapement_Module](/assets/img/oscillator.png){:height="50%" width="50%"}
{: style="text-align: center;"}

Main Spring Assembly
{: style="text-align: center;"}
![Main_spring_assembly](/assets/img/spring.png){:height="50%" width="50%"}
{: style="text-align: center;"}

When it came to designing the parts of the clock, we divided the clock into five different parts: the oscillator, 
escapement, gear box, main spring, and display. three of our group members worked on the gear train, while my partner and I worked on the rest of the clock. 
I designed our oscillating mass module, the mechanism which controls the rate of ticking in the clock. I also designed our 
main spring, which powered the clock, and then became instrumental to the display drastically simplifying our design. Rather 
than creating an entire display module which would have to connect to the gear box and travel around the main spring,
I realized that we could simply connect the output of the main spring, which was controlled by the gear box,
to an encoder wheel, creating the proper displayed time in an extremely simplistic manner. 

CAD Assembly
{: style="text-align: center;"}
![Chassis cad](/assets/img/assembly.png){:height="40%" width="40%"}
{: style="text-align: center;"}
