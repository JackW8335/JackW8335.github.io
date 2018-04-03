---
layout: post          #important: don't change this
title: "Movement in ChessCom"
date: 2018-04-03 14:35
author: Jack Watson
categories:
- Low Level Programming             #important: leave this here
img: chessCom.jpg       #place image (850x450) with this name in /assets/img/blog/
thumb: chessCom.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---

<!--more-->
### At last it moves
During the development of a test level and test pieces I used the click handler to select and then move the piece to mouse
position on the second click. The next step after this was to make it use a grid system to segment movement, this way it was more 
organised and similar to chess.

![Chess piece movement during testing]({{ "/assets/img/blog/chessMovement1.gif" | absolute_url }})

### Now to go isometric!
Once the map had been made isometric a few tweaks to the code that accessed the tile location and the offset for the piece used
were made. This along with new textures resulted in what we have now.

![Fancy textures! Oh and we nudged the map around!]({{ "/assets/img/blog/chessMovement2.gif" | absolute_url }})

