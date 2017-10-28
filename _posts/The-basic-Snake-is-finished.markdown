---
layout: post          #important: don't change this
title: "The basic snake is finished"
date: 2017-10-28 12:42
author: Jack Watson
categories:
- Low Level Programming             #important: leave this here
- Snake
img: snake.jpg       #place image (850x450) with this name in /assets/img/blog/
thumb: snake.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---

<!--more-->
I ended up making my own delta_time using the ASGE engines gametime, however I realised that I could increment a value by delta_time allowing a much easier means of knowing when the game had taken longer than a certain amount of time. Now my snake updates every 30 frames. This allows the sprite to move enough space that the previous locations to overlap, allowing the snake body to work properly.

I also added a game over game action so that the game can end. I orignally tried to make the array change size as fruit was consumed but with some research it sounds like I would have to move previous data to a new array and delete the old one. In the end I allocated 40 slots to an array holding all the playerBody information and made sure it can't go any further. Its slightly better than using the stack for everything just not the solution I orignally planned.

There was also an attempt at making a score appear but so far appending a number to a char or string hasnt worked.


![Snake]({{"/assets/img/blog/snake1.gif"| absolute_url }})

