---
layout: post          #important: don't change this
title: "More Moving"
date: 2018-04-03 14:35
author: Jack Watson
categories:
- Low Level Programming             #important: leave this here
- ChessCom
img: chessCom.jpg       #place image (850x450) with this name in /assets/img/blog/
thumb: chessCom.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---

<!--more-->
### Moving for real this time
Before pieces simply moved to wherever you clicked. But now using the same selection code from before instead of mouse positions
being passed in on click, selecting pieces calculates all the local valid positions. Passes those to the tile highlighter, which
then checks if you select a highlighted tile. In other words I coupled movement and validation checks together. 

The positions that are valid are incremented 15 times for pieces such as the queen,rook and bishop which move the length of 
the board. So unlike the pawn which has 4 constant positions. The pieces with movement across the board constantly add to the 
previous valid position by the same amount.

![Chess piece movement during testing]({{ "/assets/img/blog/chessMovement3.gif" | absolute_url }})



