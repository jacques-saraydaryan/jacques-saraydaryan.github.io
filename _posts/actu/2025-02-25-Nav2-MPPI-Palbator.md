---
layout: actu
title: Enhanced Navigation ROS2-Nav2 using MPPI and Spatio-Temporal Voxel Layed
description: > 
 Enhanced Navigation using ROS-2 - Nav2 with laser Obstacle layer (global and local costmap), Spatio-Temporal Voxel Layer (global and local costmap), MPPI Controller (PMB-2 Pal mobile based)
tags: [project]
category: actu
videotype: image
img: /assets/img/actu/robocup-pepper.jpg
video: https://www.youtube.com/embed/iOiz4mre8yw
lang: en
---
We have updated the navigation of the Palbator, [LyonTech team robot](https://robocup-lyontech.github.io/). 
With a PAL PMB2 in ROS1, we use a ros bridge to exchange laser scan, odometry, robot description and command velocity between ROS1 and ROS2.
Finally, we configure [NAV-2](https://docs.nav2.org/) using [MPPI](https://docs.nav2.org/configuration/packages/configuring-mppic.html) as the controller and add several costmap layers to the local and global costmap. 
The information from the RGB-D camera is also used to avoid 3D obstacles through a Spatio-Temporal Voxel Layer [Spatio-Temporal Voxel Layer](https://github.com/SteveMacenski/spatio_temporal_voxel_layer)
![Nav2 With MPPI and STVL](/assets/img/actu/post/nav2-MPPI-v1.jpg "Nav2 With MPPI and STVL")
