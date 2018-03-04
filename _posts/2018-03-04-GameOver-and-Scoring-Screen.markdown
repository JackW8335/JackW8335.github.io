---
layout: post          #important: don't change this
title: "GameOver and Scoring Screen"
date: 2018-03-04 10:12
author: Jack Watson
categories:
- Low Level Programming             #important: leave this here
img: BirdManPoster.jpg       #place image (450x450) with this name in /assets/img/blog/
thumb: BirdManPoster.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---

<!--more-->
### A few updates
When colliding with the monster the player instantly dies, would have prefered having invincibility frames and 3 health like most classic 
games.This way cuts out lots of work time and we are close to the deadline. A quick note to the stop watch, in the end we decided to cut it
from the game as it felt like it would only slow the pace of the game down, it's still very easy to walk around ghosts once caught as we 
have yet to program a difficulty curve.

###GAMEOVER!
After dying the user is greeted with a new gameover screen, it follows the same principle as the menu screen in that you can walk over the
buttons and press enter to interact with them.
###Score
I also added a simple scoring system that outputs what level you got to. Orignally we wanted to make the game endless with the same levels 
randomly selected. However my partner and me decided to keep the quality of the levels and changed the score system from incremting a number
everytime to just outputting the level id number. 

On a side note we also wanted to add time to the score because completeing the game faster and being rewarded with a better score seemed to
be the best incentive to producing motivation in play. Due to time constraints this has not been added but is defintely something to consider
in future development.




![Here is what losing looks like!]({{ "/assets/img/blog/birdManGameOver.gif" | absolute_url }})

