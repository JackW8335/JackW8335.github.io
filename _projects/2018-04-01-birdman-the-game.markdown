---
layout: project
title:  "Birdman Inspired Game"
date:   2018-04-01 10:47
author: Jack watson
categories:
- project
img: placeholder.jpg
thumb: placeholder.jpg
carousel:
- birdman-game.gif
- birdman-game1.gif
- birdman-game2.gif

tagged: Flat, UI, Development
---
#### Birdman Inspired Game PostMortem

This was a two person project unlike the previous two. This allowed us more flexbility with work amounts, resulting in less squares
and far more polish than my other projects. The main character had 12 sprites for each direction and each variant of walking. The
walls and floors were better than my usual green block. The ghost had animations to, all of which required an animation manager. 

We also included a scene manager which allowed each scene to have its own update, init and render functionalties. We also used unique_pointers
and vectors for this project which was a first for me, no need to worry about deallocating memory huzza.

Thanks to the irrKlang library we were also able to include sound in our game adding much need ambience to a game with horror themes.

#### Onto the actual game
An endless, horror, exploration game

Walk around the rotting theatre and collect pages of script to stave of your insanity and you try to work through the play. As you do
a ghostly figure representing your darker self will come looking for you. There are no second chances however, once caught you lose.
Find as many pages as you can and make it to the highest floor.




