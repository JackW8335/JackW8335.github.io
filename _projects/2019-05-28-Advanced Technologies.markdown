---
layout: project
title:  "Advanced Technologies"
date:   2018-04-18 10:34
author: Jack watson
categories:
- Advanced Technologies
img: AT.jpeg
thumb: AT.jpeg
carousel:
- ATProceduralBuilding.gif
- ATDeepLearning.gif
- ATSkeletal.gif

tagged: Flat, UI, Development
---
#### Procedural Building Generation

Made with the DirectX2010 SDK, a basic engine was put together that outputted a window and rendered simple models read from TXT files.
Each room was made up of three walls, a doorway and a roof. These then used the UI variables for Width, Height and Depth.

The UI was made using AntTweakBar, a free to use GUI library compatible with DirectX and OpenGL.

The building can then be exported into an OBJ and MTL file. Which can then be dragged into other tools for further use, namely when 
creating virtual environments.

#### AI Deep Learning

Using Python and Tensorflow, a convolutional network was implemented. With 5 categories: Cat, Dog, Human, Forest and City.
The network uses machine learning to roughly guess the probability of what an image is. It then outputs a save which can be used
in this case, for a Unity game which changes the playable character and background based on the input.

#### Assimp Model

Using the Open Asset Import Library or Assimp required the mesh systems to be rewritten in a different class reserved for assimp.
Each mesh was added to a vector which was then looped through to draw and render the mesh.

Before each mesh was added onto one buffer then rendered, But now each node of a model was looked at and if it contained a mesh
the mesh would be read in and stored.

