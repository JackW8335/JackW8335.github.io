---
layout: post          #important: don't change this
title: "Team Select"
date: 2018-05-12 14:37
author: Jack Watson
categories:
- Game Engine Programming           #important: leave this here
- Metrobrawl
img: SuperSmashPicture.jpg       #place image (850x450) with this name in /assets/img/blog/
thumb: SuperSmashPicture.jpg     #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---

<!--more-->
### Teams and stuff 
Currently while the team select does not wire directly into the game manager and game scene. All the combinations of the players chosen are
stored in a vector that can be used later.

All the profile pictures are UISprites that unlike the other images have had their tag set to theit fighter number. Using the col_data from 
the cursors collision data the teamview panel can then be changed to what fighter was selected. 

With the updated system now using tags rather than what images were collided with, team select now supports multiple cursors as before all 
of profile pictures that had been collided with were added to the list and looped through. This meant that if multiple cursors were 
selecting an image then all other players would be forced into using that picture.

As the player objects vector has been removed another method for detecing player amount and adjusting the UI will need to be implemented.
Efforts to update the texture assests have also been made as one can see below.

### Here what we have made so far
![]({{ "/assets/img/blog/GEP Player UI.gif" | absolute_url }})

## Upgraded art assests

Gone are the times of grey blocks. Now we have slightly coloured backgrounds and platforms like seen above

![This is another variation]({{ "/assets/img/blog/GEP Player UI2.gif" | absolute_url }})

Currently the maps are hard coded. We hope to add these as file to be read and made from.

