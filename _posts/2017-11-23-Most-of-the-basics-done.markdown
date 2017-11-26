---
layout: post          #important: don't change this
title: "Most of the basics done"
date: 2017-11-23 13:26
author: Jack Watson
categories:
- Low Level Programming             #important: leave this here
- Endless runner
img: endless_runner.jpg       #place image (450x450) with this name in /assets/img/blog/
thumb: endless_runner.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---

<!--more-->
So far I have added a basic player sprite, player movement in the form of running left and right and jumping. I am also working on the 
collisions for a basic box that I will then mass produce later on the procedurally make levels. Currently having some minor issues with
collision as moving 20 pixels per update causes the sprite to appear 20 pixels to far after collision. Making the game update anymore
would mean the game is happening to fast. I have already capped the game at 60 so I would rather leave it at that. 

Theres also the issue of making the sprite fall after walking off the block. I have reset the floor but currently jumping is the only
function that allows for the position_y to fall at an accelerated rate. One idea is to have a constant falling force and then make jumping
change it. The other option to hard code a falling function with the same code as jump only reversed. We shall see what works, if possible 
I would prefer the former idea.

Another quick message. Currently releasing the movement controls mid jump causing the running to continue after the jump. I orignally had
the opposite but to make seem like holding down A or D would continue running I coded it to allow to set movement to previous_key after
jump. 

![]({{ "/assets/img/blog/EndlessRunner1.gif" | absolute_url }})

