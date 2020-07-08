+++
abstract = "Trajectory optimization (TO) is one of the most powerful tools for generating feasible motions for humanoid robots. However, including uncertainties and stochasticity in the TO problem to generate robust motions can easily lead to intractable problems. Furthermore, since the models used in TO have always some level of abstraction, it can be hard to find a realistic set of uncertainties in the model space. In this paper we leverage a sample-efficient learning technique (Bayesian optimization) to robustify TO for humanoid locomotion. The main idea is to use data from full-body simulations to make the TO stage robust by tuning the cost weights. To this end, we split the TO problem into two phases. The first phase solves a convex optimization problem for generating center of mass (CoM) trajectories based on simplified linear dynamics. The second stage employs iterative Linear-Quadratic Gaussian (iLQG) as a whole-body controller to generate full body control inputs. Then we use Bayesian optimization to find the cost weights to use in the first stage that yields robust performance in the simulation/experiment, in the presence of different disturbance/uncertainties. The results show that the proposed approach is able to generate robust motions for different sets of disturbances and uncertainties."
abstract_short = ""
authors = ["Mohammad Hasan Yeganegi, Majid Khadiv, S. Ali A. Moosavian, Jia Jie Zhu, Andrea Del Prete, Ludovic Righetti"]
date = "2019-07-01"
image_preview = "2019_humanoids_yeganegi.png"
math = true
publication_types = ["2"]
publication = "*2019 IEEE-RAS 19th International Conference on Humanoid Robots*"
publication_short = "*Humanoids*"
selected = false
title = "Robust Humanoid Locomotion Using Trajectory Optimization and Sample-Efficient Learning"
url_code = ""
url_dataset = ""
url_pdf = "https://arxiv.org/pdf/1907.04616.pdf"
url_project = ""
url_slides = ""
url_video = ""

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

[header]
image = "2019_humanoids_yeganegi.png"
caption = ""

+++
