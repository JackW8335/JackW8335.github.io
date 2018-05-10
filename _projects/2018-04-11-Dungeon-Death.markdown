---
layout: project
title:  "Dungeon Death"
date:   2018-04-01 11:32
author: Jack watson
categories:
- Low Level Programming
- Dungeon Death
img: dungeon_death.jpg
thumb: dungeon_death.jpg
carousel:
- dungeon-death1.gif
- dungeon-death2.gif
- dungeon-death3.gif

tagged: Flat, UI, Development
---
#### Dungeon Death PostMortem
There were some struggles with memory allocation when it came to placing enemies in rooms but eventually I got my head around using the .get() function more for unique pointer when creating getters, got stuck in using std::move for a time. 

My ascii art doesnt fit the panels
but I like the extra detail provided by ascii artists found online so I kept them. The main image in the player panel is a crusader from the Darkest Dungeon. During development updating the ASGE engine caused errors with the key handler but changing the value in the static cast to use const fixed that.

In future it would be interesting to make the dungeon bigger,  more random and data driven (which enemies already are by using 
json).

#### Onto the actual game
An endless, horror, dungeon exploration game

Venture through the dungeon defeat the beasts that lurk inside and earn your freedom.




