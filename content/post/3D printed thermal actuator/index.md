---
title: 3D printed mesorobot with built-in actuators
subtitle: ""

# Summary for listings and search engines
summary: Binary manipulators are a particular kind of discrete device in which actuators have two stable states. Major benefits of binary manipulators are that they can be operated without extensive feedback control and their task repeatability is very high.

# Link this post with a project
projects: []

# Date published
date: '2020-12-13T00:00:00Z'

# Date updated
lastmod: '2020-12-13T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: Benjamin Calmé'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

---

## Overview

In the literature, the first approach considered for deployment in narrow and tortuous environments is based on the use of a hyper-redundant architecture. However, this type of architecture becomes costly and complex to assemble when downscaling is considered. Given these constraints, other approaches have been considered, such as continuum robots. Examples include a cable robot and a concentric tube robot. The problem with these architectures is the complexity of modelling them due to significant non-linearity and the use of complex control strategies.
We are therefore interested in achieving these motions while simplifying the control law. To do this, we have focused on a particular type of robot, digital robots.
The main advantages of binary manipulators are that they can be used without significant feedback ; 
and the repeatability of their tasks is very high.
This is a bottom-up approach in which we start by designing the module before designing the robot. 
The problem is that two stable states are not an optimal solution when it comes to tracking a trajectory. This requires the use of two joints operating in opposition.
Hence our proposal to design a modular structure based on 3-state modules.
In addition, the use of a 3-state module offers an advantage in terms of the number of configurations that the robot can perform. 
For example, for a robot with 8 modules, there are 26 times more configurations that can be carried out for a robot with 3 state modules.

We therefore designed a module based on a compliant. This was then used to design our robotic architecture, which we validated experimentally.

## Get Started

- 📚[Towards a compact XYZθ positioning system with built-in actuators using 3D printing of conductive polymer](https://link.springer.com/article/10.1007/s12213-023-00159-4)
- 💬[Towards a compact and low-cost mesoscopic XY positioning system using 3D printing of conductive polymers](https://ieeexplore.ieee.org/document/9870471)


