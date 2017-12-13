---
layout: post          #important: don't change this
title: "Moving enemies and a menu"
date: 2017-12-13 16:58
author: Jack Watson
categories:
- Low Level Programming             #important: leave this here
- Endless runner
img: endless_runner.jpg       #place image (450x450) with this name in /assets/img/blog/
thumb: endless_runner.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---

<!--more-->
Enemies spawn randomly and if hit cause the game over screen, after which you can exit or restart the game. Restarting was fairly simple all
I did was move the player back to their orignal position and make the obstacles move past -100 which is the limit for spawning new terrain
in my endlessMap function. A main menu was also added which allows you to hit play or exit but with a slightly different UI (Blue instead
of red). It might be similar to the game over screen but not been launched into the game straight away if important as to give the player
time to prepare before playing.

I just made two images and text on them, rather than rendering text in game. A background sprite then switches between nullptr during play
menu on beginning and game over when you die from hitting an enemy.

![UML]({{ "/assets/img/blog/EndlessRunner3.gif" | absolute_url }})

