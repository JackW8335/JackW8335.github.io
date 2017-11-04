---
layout: post          #important: don't change this
title: "Starting Snake"
date: 2017-10-06 10:51
author: Jack Watson
categories:
- Low Level Programming             #important: leave this here
- Snake
img: snake.jpg       #place image (850x450) with this name in /assets/img/blog/
thumb: snake.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---

<!--more-->
Firstly, I was unable to directly use the renderer inside of my player class using a get function so I decided to use a get function to place and render my sprite initially in the renderer function, its only afterwards that the set function is used to allocate the sprites image and position. I also included the engines keys so that I could use keybindings in my update function to change player position, in other words I created a player movement function. I also added the ability for the snake to appear on the opposite side of the screen it goes to far in one direction. 
