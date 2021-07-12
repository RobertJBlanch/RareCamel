---
layout: single
title:  "Unity Object Placer"
date:   2021-07-09 13:23:24 +1000
categories: jekyll update
---

In this series, we are going to attempt to create an object placer developer tool for Unity,
with the aim of selling the tool on Unity's asset store. Think of placing buildings in a Real-time strategy game or
placing furniture in The Sims. We want a complete system where developers can simply import the asset, designate prefabs to be placed,
immediately have realtime object placement.

To truely dominate the market for this tool, we will need a number of features that gives developers a number of options:

- Place objects on terrain
- Grid system with snapping
- Auto grid detection for prefabs/meshes (Think a 100x200x200 model will auto fit into a 1x2x2 grid)
- Shader for placement

<video autoplay loop muted playsinline width="780" height="440">
    <source src="/assets/videos/objectplacer-shader.m4v"/>
    <!-- <source src="/assets/video/shadergifHQSmall.webm"/> -->
</video>


<!-- 
GIF

<p align="center">
<img align="" height='150px' src="/assets/video/gif2.gif" />
</p> -->

