---
title: "Newtonian Binary Star System Simulation Framework"
date: 2024-07-16T04:00:00+07:00
slug: /binary-star-system-simulation/
description: A framework for a realistic astrophysical simulation of a Binary Star System
  written in Python.
image: images/Binary Star.jpeg
caption: "Artist’s impression of the exotic binary star system AR Scorpii. Credit: M. Garlick/University of Warwick, ESA/Hubble."
categories:
  - astro
tags:
  - Gravity
  - matplotlib
  - Python
  - Astrophysics
  - astronomy
  - feature
draft: false
---

## Binary Stars?

Simply put, they are two stars revolving around each other. As a matter of fact, it is [estimated that 85%](https://www.space.com/22509-binary-stars.html) of stars in the universe are Binary Star Systems or more!  We get many fascinating effects from this type system.

We see the system as one source of light because of the massive distance between us and the stars; when you look at your LED light bulb you don't see each LED, you see their light as one source.

> Did you know that Sirius, the brightes "star" in the night sky, isn't a star! It's a Binary Star System: two stars that are graviationally bound together ([Read More](https://en.wikipedia.org/wiki/Binary_star)).

{{< image-caption 
   src="https://blog.geosalib.com/images/Sirius_A_and_B_artwork.jpg" 
   alt="An Artist's Impression of Sirius A and Sirius B. NASA, ESA and G. Bacon (STScI), 2005." 
   caption="An Artist's Impression of Sirius A and Sirius B. NASA, ESA and G. Bacon (STScI), 2005." >}}


### Detecting The Wandering Couples 💕

Well, if we only see them as one light source how do we know if this is just a single star or a Binary System or a "party" of them?

We get out our nice and precise telescope (no rhyme intended)!

The way to detect these is by using precise equipment that can detect the faintest of brightness changes over time (see the image below) caused by eclipses. If the luminosity of the star changes periodically, it's a star system, huzzah! Further careful analysis of the luminosity over time graph will tell us if it's a Binary Star System or if it's a bigger party of "fireballs."

{{< image-caption 
   src="https://blog.geosalib.com/images/luminosity_graph.jpeg" 
   alt="Light curve of binary star Kepler-16. NASA, 2013." 
   caption="Light curve of binary star Kepler-16. NASA, 2013." >}}


### The Simulation Framework

I made a framework for a realistic astrophysical simulation of a Binary Star System, written in Python using the matplotlib library. It has the orbit data of the [Sirius Binary System](https://en.wikipedia.org/wiki/Sirius), a random stable system, and you can enter your own data and try to find a stable orbit.

You can find the code for the simulation [here](https://github.com/Geo-sudo/Computational-Astrophysics/tree/main/Binary%20Star).
