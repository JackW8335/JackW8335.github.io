---
layout: post          #important: don't change this
title: "Added a cold fruit"
date: 2017-11-04 13:26
author: Jack Watson
categories:
- Low Level Programming             #important: leave this here
- Snake
img: snake.jpg       #place image (850x450) with this name in /assets/img/blog/
thumb: snake.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---

<!--more-->
I was able to make a power fruit class that inherits from my fruit class. All I added on top was a duration for how long the fruit will last
Now if the player eats the fruit there speed (the refresh rate) of the game goes from 20 to 10 allowing them to have more time when deciding
which direction to go in.

I also moved most of the inital code base into an initSprite function to stop constantly making new sprites when it wasnt needed. Apart
from the snake body which constantly grows the rest are initialised at the beginning inside of init and movement still remains inside of
the old drawSprite function.

I also fixed the score system. I simply std::string score_counter = std::to_string(score); to make my score into a string and then made 
a char pointer const char * c = score_counter.c_str(); equal to it. This is outputted using the renderText function in the ASGE engine
![Snake]({{ "/assets/img/blog/snake2.gif" | absolute_url }})
