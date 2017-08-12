+++
abstract = "Task-Space Inverse Dynamics (TSID) is a well-known optimization-based technique for the control of highly-redundant mechanical systems, such as humanoid robots.  One of  its  main  flaws  is  that  it  does  not  take  into  account  any  of the  uncertainties  affecting  these  systems:  poor  torque  tracking, sensor noises, delays and model uncertainties. As a consequence, the  resulting  control-state  trajectories  may  be  feasible  for  the ideal  system,  but  not  for  the  real  one.  We  propose  to  improve the  robustness  of  TSID  by  modeling  uncertainties  in  the  joint torques,  either  as  Gaussian  random  variables  or  as  bounded deterministic variables. Then we try to immunize the constraints of the system to any—or at least most—of the realizations of these uncertainties.  When  the  resulting  optimization  problem  is  too computationally  expensive  for  online  control,  we  propose  ways to  approximate  it  that  lead  to  computation  times  below  1  ms. Extensive  simulations  in  a  realistic  environment  show  that  the proposed  robust  controllers  greatly  outperform  the  classic  one, even when other unmodeled uncertainties affect the system (e.g. errors in the inertial parameters, delays in the velocity estimates)."
abstract_short = "We exploited robust optimization techniques, either stochastic or worst-case, to improve the robustness of Task-Space Inverse Dynamics (TSID), a well-known control framework for legged robots. We modeled uncertainties in the joint torques, and we immunized the constraints of the system to any of the realizations of these uncertainties. Extensive simulations in a realistic environment show that the proposed robust controllers greatly outperform the classic one."
authors = ["Andrea Del Prete", "Nicolas Mansard"]
date = "2016-10-01"
image_preview = ""
math = true
publication_types = ["2"]
publication = "*IEEE Transaction on Robotics*"
publication_short = "*T-Ro*"
selected = true
title = "Robustness to Joint-Torque-Tracking Errors in Task-Space Inverse Dynamics"
url_code = ""
url_dataset = ""
url_pdf = "http://hal.archives-ouvertes.fr/hal-01241974/document"
url_project = ""
url_slides = ""
url_video = "https://www.youtube.com/watch?v=pnar5WQY5Vg"

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

[header]
image = "30_robots_walking.jpg"
caption = "Simulation of 30 HRP-2 robots walking in the presence of uncertainties, the goal being to compare the classic TSID controller (left line, gray heads) to the proposed robust TSID controllers: stochastic (central line, green heads) and worst-case (right line, red heads). Some of the simulation results can be seen in the accompanying video."

+++
{{< youtube pnar5WQY5Vg >}}
