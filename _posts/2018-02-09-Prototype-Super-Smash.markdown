---
layout: post          #important: don't change this
title: "Prototype Super Smash"
date: 2018-02-17 10:33
author: Jack Watson
categories:
- Game Engine Programming            #important: leave this here

img: SuperSmashPicture.jpg       #place image (850x450) with this name in /assets/img/blog/
thumb: SuperSmashPicture.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---

<!--more-->
So far I have created basic maps out of white blocks based on three from the super smash games, battlefield, final destination and luigi's 
mansion. A game manager is kept throughout the scenes and loads them via page up and down for going back and forth through the list. 
I also changed the movement to be transform based so that when the key is released there is no intertia caused by remaining momentum from 
the physics used in addForce or velocity.

Punches simply apply a force to the opposing player based on a variable the player has called cumaltive force which acts similar to the 
normal game by increasing the more you get hit, gradually leading to being shot of the screen and respawning.

These is what it looks like so far on my branch:



![]({{ "/assets/img/blog/SuperSmashPrototype.gif" | absolute_url }})

