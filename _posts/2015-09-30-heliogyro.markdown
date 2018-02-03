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
<p align="center">
  <img src="http://hanhsun.github.io/assets/images/Project/heliogyro_solar_pressure.png">
</p>
<figcaption class="caption">Coupled bending-twisting model with solar pressure</figcaption>

## In a Nutshell
The project focused on a solar sailing concept using solar pressure as main propulsion. I was part of the Structural Dynamics group at NASA Langley (LaRC) group that worked on the vehicle simulation and I developed a discrete time model for the flexible beam dynamics and applied linear system identification to analyze the mode shapes of the spacecraft.

I analyzed an envelope of stability and applied model based predictive control with root piezocomposite active twist controllers to control the flexible blade using Matlab/Simulink. The simulation showed that root twist controllers are feasible of stabilizing a flexible blade while providing good performance.

Here is an example of the single blade six mass coupled bending-twisting simulation:

<p align="center">
  <img src="http://hanhsun.github.io/assets/images/Project/SixMassSinglebladesim.gif">
</p>

## Key Challenges
* Deriving the coupled flexible structural equations.
* Analyzing the effect of solar pressure on the coupled structure and specifying the dynamic modal changes associated to the structure deformation.
* Identifying a linearized model for the flexible nonlinear structure.
* Applying Model Predictive Control (MPC) to stabilize the flexible beam.

## More Info
More information on this work can be found in my publications
- [*Challenges Associated with System Identification and Control of a Heliogyro Membrane Blade*](https://link.springer.com/chapter/10.1007/978-3-642-34907-2_43)
- [*Adaptive Control of a Heliogyro Membrane Blade*](http://articles.adsabs.harvard.edu/cgi-bin/nph-iarticle_query?2014ESASP.727E.186L&amp;data_type=PDF_HIGH&amp;whole_paper=YES&amp;type=PRINTER&amp;filetype=.pdf)
