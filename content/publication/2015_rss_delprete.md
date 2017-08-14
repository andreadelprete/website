+++
abstract = "Task-Space Inverse Dynamics (TSID) is a well-known optimization-based technique for the control of highly-redundant mechanical systems, such as humanoid robots. One of its main flaws is that it does not take into account any of the uncertainties affecting these systems: poor torque tracking, sensor noises, delays and model uncertainties. As a consequence, the resulting control trajectories may be feasible for the ideal system, but not for the real one. We propose to improve the robustness of TSID by modeling uncertainties in the joint torques as additive white random noise (similarly to LQG). This results in a stochastic optimization problem, in which we can maximize the probability to satisfy the inequality constraints (i.e. to be feasible). Since computing this probability is computationally expensive, we propose three ways to approximate it that are much faster to compute and that we can then use for online control (resolution time below 1 ms). Simulation results show that taking robustness into account greatly increases the chances to have feasible control trajectories (even when the uncertainties affecting the system are not the one modeled in the controller)."
abstract_short = ""
authors = ["Andrea Del Prete", "Nicolas Mansard"]
date = "2015-07-01"
image_preview = ""
math = true
publication_types = ["1"]
publication = "*Robotics, Science and Systems*"
publication_short = "*RSS*"
selected = false
title = "Addressing Constraint Robustness to Torque Errors in Task-Space Inverse Dynamics"
url_code = ""
url_dataset = ""
url_pdf = "https://hal.inria.fr/hal-01109375v2/document"
url_project = ""
url_slides = ""
url_video = "https://www.youtube.com/watch?v=ZJpv7K452_Q"

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

#[header]
#image = "2016_auro_focchi.jpg"
#caption = ""

+++

{{< youtube ZJpv7K452_Q >}}
