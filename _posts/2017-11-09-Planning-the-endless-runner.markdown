---
layout: post          #important: don't change this
title: "Planning the endless runner"
date: 2017-11-09 13:26
author: Jack Watson
categories:
- Low Level Programming             #important: leave this here
- Endless runner
img: endless_runner.jpg       #place image (450x450) with this name in /assets/img/blog/
thumb: endless_runner.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---

<!--more-->
The begin with a basic runner is a player jumping over or below obstacles while collecting coins or seeing how far one can go without stopping
Instantly the obvious things to have are a player and obstacles class each with positions and sprites of there own. However I think i'm
going to try make an endless runner thats has you face multiple enemies coming your way that you use abilities to defeat. The overall score will be based on distance travelled but perhaps having a counter for enemies defeated would be good to, as players can then compare
enemy kills.

![UML]({{ "/assets/img/blog/endlessRunnerUML.png" | absolute_url }})

