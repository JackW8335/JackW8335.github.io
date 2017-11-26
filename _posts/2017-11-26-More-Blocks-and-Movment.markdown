---
layout: post          #important: don't change this
title: "More blocks and movement"
date: 2017-11-26 13:30
author: Jack Watson
categories:
- Low Level Programming             #important: leave this here
- Endless runner
img: endless_runner.jpg       #place image (450x450) with this name in /assets/img/blog/
thumb: endless_runner.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---

<!--more-->
The collisions are still not working well. As one can see by the gif colliding with the blocks sets the player y coordinate to the
block y, this was orignally because jumping at a ever changing pace due to gravity caused visible issues where the player would sink into
another block or the floor. However this now causes this problem. Due to time constraints im trying to get the game running before I fix
this.

I intend to add: 
-Enemies to dodge that deal damage adding an end to the game
-A highscore save system and score system based on distance travelled
-If possible I would also like to add a restart option

![]({{ "/assets/img/blog/endlessRunner2.gif" | absolute_url }})

