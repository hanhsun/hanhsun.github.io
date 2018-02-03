---
title: "Heliogyro Solar Sail"
layout: post
date: 2015-09-30 21:10
tag:
- solar-sail
- simulation
image: /assets/images/Project/supercub.png
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
description: "This is a simple and minimalist template for Jekyll for those who likes to eat noodles."
category: project
author: jacklu
externalLink: false
---

![Screenshot](/assets/images/Project/heliogyro_solar_pressure.png)
<figcaption class="caption">Coupled bending-twisting model with solar pressure</figcaption>

## In a Nutshell
The project focused on a solar sailing concept using solar pressure as main propulsion. I was part of the Structural Dynamics group at NASA Langley (LaRC) group that worked on the vehicle simulation and I developed a discrete time model for the flexible beam dynamics and applied linear system identification to analyze the mode shapes of the spacecraft.

I analyzed an envelope of stability and applied model based predictive control with root piezocomposite active twist controllers to control the flexible blade using Matlab/Simulink. The simulation showed that root twist controllers are feasible of stabilizing a flexible blade while providing good performance.

Here is an example of the single blade six mass coupled bending-twisting simulation:

![Screenshot](/assets/images/Project/SixMassSinglebladesim.gif)


<p align="center">
  <img src="hanhsun.github.io/assets/images/Project/SixMassSinglebladesim.gif">
</p>

## Key Challenges
* Imaging mission planning incorporating sensor settings
* Quantification of the growth and development of field crops as affected by soil, irrigation and crop management strategies
* Increasing **reliability** of the collected image quality through image pre-processing and image post processing

## More Info
More information on the system I developed can be found in my [Development and testing of a customized low-cost unmanned aircraft system based on multispectral and thermal sensing for precision agriculture applications-2017](http://ieeexplore.ieee.org/abstract/document/7991494/) paper.
