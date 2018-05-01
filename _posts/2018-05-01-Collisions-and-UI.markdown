---
layout: post          #important: don't change this
title: "Collisions and UI"
date: 2018-05-01 11:27
author: Jack Watson
categories:
- Game Engine Programming           #important: leave this here
- Metrobrawl
img: SuperSmashPicture.jpg       #place image (850x450) with this name in /assets/img/blog/
thumb: SuperSmashPicture.jpg     #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---

<!--more-->
### First Collisions
To begin there was simply bounding boxes made within a collider class. After all the colliders are instanciated inside the game they are
added to a vector which is copied to the collision manager, which detects if the bounding boxes of any objects with colliders overlap.

For the collision action the object in question is moved by the difference in origins divivded by 100, Making it look like the players have
stopped when in reality they are moving a fraction.

In order to keep track of which collider belonged to which object ID's were given and assigned based on player object amount e.g if 
one player was made then the colliders would be assinged tag 0 as that was the size of the array before being made, arrays start at zero
so this worked in our benefit.

### UI Stuff
For creating the UI for coloured boxes and the numbers inside them I reused the UI label and sprite classes from when we created the basic 
main menu. The sprites are created but only instanciated up to player number, similarly the text is only set based on player number e.g.
players means three coloured panels with three text.

Note:
All the text panels are actually instanciated, however only panels leading up to the player amount have their text set and updated.


### Here what we have made so far
You might be able to notice some collisions, we intend to replace the collision system as currently its very buggy and make it physics 
driven. Apart from a slight issue with xutility the UI runs fine as seen below.
![]({{ "/assets/img/blog/GEP collisions and ui.gif" | absolute_url }})

