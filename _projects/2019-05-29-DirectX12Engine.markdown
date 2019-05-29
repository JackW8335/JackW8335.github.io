---
layout: project
title:  "Game Engine with DirectX12"
date:   2018-04-18 10:09
author: Jack watson
categories:
- Game Engine Programming
- DirectX12
img: SuperSmashPicture.jpg
thumb: GEPFinalRelease.gif
carousel:
- ChessCom1.gif
- GEP collisions and ui.gif
- GEPFinalRelease.gif

tagged: Flat, UI, Development
---
#### Unity Prototype
To get a quick visualisation for the product we got to work on trying to get the punching working for the players aswell as scaling the 
knockback like in SuperSmash.

![]({{ "/assets/img/blog/SuperSmashPrototype.gif" | absolute_url }})


#### Straight into DirectX12

Other than having a brief dive into the game design logic of SuperSmash not much was done with Unity. As such we first had to overcome a
technical hurdle by learning directx12. Once we had a window rendering objects, we replaced the objects with characters.

However, these characters needed to be animated, so we created a class that went through an array of images to create animations.

Collisions took a while to configure, as can be seen in the gifs above, sometimes players sink into the floor, or players get stuck together.

Eventually we added a player select screen, and multiple menus. 

#### Final product
A basic fighting game with inspiration from SuperSmash, theres powerups, 4 characters and the combat boils down to hitting each other
with one punch move.

