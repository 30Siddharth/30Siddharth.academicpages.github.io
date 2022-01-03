---
layout: archive
title: "Path Planning & Controls"
# permalink: /projects/
author_profile: true
---

# Vector Field Navigation
Vector filed based navigation technique is heavily used in legged robotics and indoor robotics. During my time at UPenn I worked on developing a robot from scratch for the COD style robo-war. For the prupose of autonomously capturing the target we decided to use a vector field based approach since the target is always fixed. Since the motion was restricted to a surface, it was 3D problem. The position and orientation were measured using HTC vive and IR-sensors. I placed two transducers along the length to build a sensor that could capture the position and the orientation. 

# Graph Search Methods for Planning
While planning in 2D is plausible, for systems with higher dimensions this can be infeasible. For real time solutions the amount of computation power required outpaces the form factor and resources available by a considerable amount. This is where graph search based methods come into the picture. Discetizing the feasible state space give us the nodes of the graphs. I have had the chance to work with Dijkstra's and A-star planning and testing my code in terms of implemntation on Crazyfly 2.0 as a part of my coursework of MEAM 620 at UPenn. 

# 