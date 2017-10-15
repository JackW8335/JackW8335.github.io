---
layout: post          #important: don't change this
title: "Finally-got-delta-time-working"
date: 2017-10-15 10:01
author: Jack Watson
categories:
- Low Level Programming             #important: leave this here
- Snake
img: snake.jpg       #place image (850x450) with this name in /assets/img/blog/
thumb: snake.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---

<!--more-->
I was trying to use a private object inside of the game class, this resulted in delta_time returning zero milliseconds as I was calling it while inside the data function. So instead to access delta_time I used the update function in game and used parameters for gametime adding the pointer time to the function and passed that into my players updatePosition function. Now my character moves based on time I was able to run it at the same speed on my computer aswell as my laptop.

Now I can start working on the snake body. My current plan is to save the previous position of the player and other parts of the snake 
so that every update they move the previous position. In theory this means the snake body should follow the next part along starting
with the head.



![Snake]({{ "/assets/img/blog/snake.gif" | absolute_url }})

