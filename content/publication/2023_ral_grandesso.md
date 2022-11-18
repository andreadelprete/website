+++
abstract = "This paper presents a novel algorithm for the continuous control of dynamical systems that combines Trajectory Optimization (TO) and Reinforcement Learning (RL) in a single framework. The motivations behind this algorithm are the two main limitations of TO and RL when applied to continuous nonlinear systems to minimize a non-convex cost function. Specifically, TO can get stuck in poor local minima when the search is not initialized close to a good minimum. On the other hand, when dealing with continuous state and control spaces, the RL training process may be excessively long and strongly dependent on the exploration strategy. Thus, our algorithm learns a good control policy via TO-guided RL policy search that, when used as initial guess provider for TO, makes the trajectory optimization process less prone to converge to poor local optima. Our method is validated on several reaching problems featuring non-convex obstacle avoidance with different dynamical systems, including a car model with 6d state, and a 3-joint planar manipulator. Our results show the great capabilities of CACTO in escaping local minima, while being more computationally efficient than the DDPG RL algorithm."
abstract_short = ""
authors = ["Gianluigi Grandesso, Gastone P. Rosati Papini, Patrick M. Wensing, Andrea Del Prete"]
date = "2022-11-12"
image_preview = "2023_ral_grandesso.png"
math = true
publication_types = ["2"]
publication = "*Robotics and Automation Letters (under review)*"
publication_short = "*RAL* (under review)"
selected = false
title = "CACTO: Continuous Actor-Critic with Trajectory Optimization-Towards global optimality"
url_code = ""
url_dataset = ""
url_pdf = "https://arxiv.org/pdf/2211.06625.pdf"
url_project = ""
url_slides = ""
url_video = ""

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

[header]
image = "2023_ral_grandesso.png"
caption = ""

+++
