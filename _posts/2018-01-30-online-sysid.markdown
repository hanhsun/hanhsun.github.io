---
title: "Online Near Real-Time System Identification on a Supercub SUAS"
layout: post
date: 2018-01-30 22:10
tag: Real-Time Modeling
image: /assets/images/Project/jack_cub.jpg
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
description: "This is a simple and minimalist template for Jekyll for those who likes to eat noodles."
category: project
author: jacklu
externalLink: false
---

![Screenshot](/assets/images/Project/jack_cub.jpg)

## In a Nutshell
The goal of this project is to develop the capability of performing online system identification using Commercial-Off-The-Shelf (COTS) products on a Small scale Unmanned Aircraft System (UAS).

The final version of the system is capable of identifying and modifying vehicle state-space models while the UAV is in the air. Different inputs were tested and multiple flight models were identified using the system.  

## Key Challenges
* Porting all the **Matlab** system identification code to a **Python**.
* Building a customized data acquisition system that supports enough sensors at a high frequency. [DFTI](https://tamu-vscl.github.io/dfti/index.html) was developed and used.
* Designing a user friendly interface to show the identified model on the Ground Control Station (GCS).
* Real-time calculating and updating vehicle dynamic models for flight control.

A snapshot of the communication GUI is shown in Figure 1
![Markdowm Image](/assets/images/Project/Clarkview.png)
<figcaption class="caption">Figure 1</figcaption>

## More Info
More information on the system I developed can be found in my [SciTech 2018 paper](\assets\doc\Online_SysID_Scitech_2018.pdf).

Also feel free to contact me via email!
