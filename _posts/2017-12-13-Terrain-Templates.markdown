---
layout: post          #important: don't change this
title: "Terrain Templates"
date: 2017-12-13 17:11
author: Jack Watson
categories:
- Low Level Programming             #important: leave this here
- Endless runner
img: endless_runner.jpg       #place image (450x450) with this name in /assets/img/blog/
thumb: endless_runner.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---

<!--more-->
I created two function in game that create terrain, one called stairs and one called corridor. What they create is self explanatory and can
be seen below. This is done randomly using the functions that run as part of a switch case who's condition is an integer that picks between
0 and 1. 

Procedurally generating games atleast from a basic stand point, can be seen as spawning randomly placed assests using algorithms to make
sure they meet a required condition such as how close and far they spawn to each other. In an ideal world I would use "sliders" in the form
of variables and make the spawn spawn soley on algorithms. However due to time constraints ill have to settle with spawning prefab like
structures randomly throughout the level.

![I was Running]({{ "/assets/img/blog/EndlessRunner4.gif" | absolute_url }})

