---
layout: post          #important: don't change this
title: "Planning the Birdman Game"
date: 2018-02-011 10:33
author: Jack Watson
categories:
- Low Level Programming           #important: leave this here
img: BirdmanPoster.jpg       #place image (850x450) with this name in /assets/img/blog/
thumb: BirdManPoster.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---

<!--more-->
Our group has created a basic UML to show the plan for implementing the game.The game and gamestates will inherit from a gamestates class
this way we can use a different update, init etc function for each state, less messy with if statements and switches everywhere. The gameojects
will inherit from the gameobject class, we currently want some basic power up items which will be added later.



![UML]({{ "/assets/img/blog/BirdManUML" | absolute_url }})

