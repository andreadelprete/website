+++
# Date this page was created.
date = "2017-08-27"

# Project title.
title = "Robust Robotics"

# Project summary to display on homepage.
summary = "Nowadays legged robots are capable of performing locomotion and manipulation in semi-structured environments, but with a low level of reliability, which makes their application in disaster-recovery scenarios difficult, if not impossible. However, if we look at the results that researchers in robotics and animation have achieved in simulation, we can see that simulated robots/avatars can easily and reliably perform dynamic movements such as walking, running, jumping, kicking. What is preventing real robots from showing similar performance?"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "30_robots_walking.jpg"

# Tags: can be used for filtering projects.
tags = ["robust-optimization", "robust-control"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++

# Objectives
The goal of this project is to improve performance and reliability by accounting for uncertainties. The current approach in robotics is to neglect uncertainties and just try to compensate for them by means of sensory feedback. This has led us to the paradigm “the faster, the better”, because it is only through fast feedback loops that nowadays robots are able to cope with uncertainties. We believe that identifying uncertainties and taking them into account in our control/planning algorithms is our best chance to overcome this limiting paradigm.

# Previous Work
### Robustness to Joint-Torque Tracking Errors
My first paper on this subject has been published at RSS 2015 (["Addressing Constraint Robustness to Torque Errors in Task-Space Inverse Dynamics"]({{< ref "publication/2015_rss_delprete.md" >}})), and then its extension in IEEE Transaction of Robotics ([Robustness to Joint-Torque-Tracking Errors in Task-Space Inverse Dynamics]({{< ref "publication/2016_tro_robust_inv_dyn.md" >}})). In these papers we dealt with the robustness of inverse-dynamics control to uncertainties in the joint-torque tracking. The problem was tackled using either a worst-case approach, or a stochastic approach. The resulting controllers have been compared against the classic non-robust approach through thousands of simulations with the humanoid robot HRP-2, empirically proving the superior performance of the proposed approaches.

### Robustness to Inertial Parameter Errors
Later, in 2016, I started investigating the problem of inertial parameter errors (see [Robustness to Inertial Parameter Errors for Legged Robots Balancing on Level Ground]({{< ref "publication/2017_icinco_giftsun.md" >}})). These parameters enter nonlinearly in the robot dynamics equations, which makes them hard to deal with. However, the position and velocity of the center of mass (CoM) of the robot are (almost) linear functions of these parameters, so we can easily model the effect of inertial parameters errors on these quantities. Since standard balancing criteria for legged robots on level ground are based on the CoM position and velocity, we could exploit robust optimization technique to increase the robustness of the robot balancing.

# Future Work
The above-mentioned work has just began scratching the surface of this huge problem. This project aims to understand whether robust optimization could be the right tool to account for the countless uncertainties affecting legged robots, such as modeling errors, actuation inaccuracies, estimation uncertainties and delays. Many questions still need an answer, such as:

* What limits us in transferring from simulations to real robots? Is it modeling assumptions / bandwidth / uncertainty? 
* Is robust optimization fast enough for application in control? 
* Can improved robustness outweigh slower control rates? 
* How to model and identify uncertainties? 
* Which uncertainties are the most important to take into account? 
* Are there modeling assumptions that make computation hard, but are not so important on real systems?

Some of these questions have arisen during discussion with [Alexander Herzog](http://www-clmc.usc.edu/Main/AlexanderHerzog), while we were organizing a workshop at ICRA 2016, titled ["Robust Optimization-Based Control and Planning for Legged Robots"](http://webdav.tuebingen.mpg.de/robust_mpc_legged_robots/).