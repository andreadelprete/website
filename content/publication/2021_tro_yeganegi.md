+++
abstract = "Model predictive control (MPC) has shown great success for controlling complex systems such as legged robots. However, when closing the loop, the performance and feasibility of the finite horizon optimal control problem solved at each control cycle is not guaranteed anymore. This is due to model discrepancies, the effect of low-level controllers, uncertainties and sensor noise. To address these issues, we propose a modified version of a standard MPC approach used in legged locomotion with viability (weak forward invariance) guarantees that ensures the feasibility of the optimal control problem. Moreover, we use past experimental data to find the best cost weights, which measure a combination of performance, constraint satisfaction robustness, or stability (invariance). These interpretable costs measure the trade off between robustness and performance. For this purpose, we use Bayesian optimization (BO) to systematically design experiments that help efficiently collect data to learn a cost function leading to robust performance. Our simulation results with different realistic disturbances (i.e. external pushes, unmodeled actuator dynamics and computational delay) show the effectiveness of our approach to create robust controllers for humanoid robots."
abstract_short = ""
authors = ["Mohammad Hasan Yeganegi, Majid Khadiv, Andrea Del Prete, S. Ali A. Moosavian, Ludovic Righetti"]
date = "2020-10-09"
image_preview = "2021_tro_yeganegi.png"
math = true
publication_types = ["2"]
publication = "*IEEE Transactions on Robotics* (under review)"
publication_short = "*T-Ro* (submitted to)"
selected = false
title = "Robust walking based on MPC with viability-based feasibility guarantees"
url_code = ""
url_dataset = ""
url_pdf = "https://arxiv.org/pdf/2010.04514.pdf"
url_project = ""
url_slides = ""
url_video = ""

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

[header]
image = "2021_tro_yeganegi.png"
caption = ""

+++
