---
layout: post          #important: don't change this
title: "Scoring High"
date: 2017-12-13 17:
author: Jack Watson
categories:
- Low Level Programming             #important: leave this here
- Endless runner
img: endless_runner.jpg       #place image (450x450) with this name in /assets/img/blog/
thumb: endless_runner.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---

<!--more-->
I added a basic score system that increments score by one every 30 frames. This is then stored in a txt file via the use of fstream. 
The high score refreshes after every defeat but only if its higher than the current one. You can only see the highscore on the main menu
which can't be accessed after you start playing only after re running the game. 

On the gif below my score changes after beating the previous. The score can be seen throughout on the left side of the screen.

![Beat that!]({{ "/assets/img/blog/EndlessRunner5.gif" | absolute_url }})

