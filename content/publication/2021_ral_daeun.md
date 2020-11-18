+++
abstract = "One challenge of legged locomotion on uneven terrains is to deal with both the discrete problem of selecting a contact surface for each footstep and the continuous problem of placing each footstep on the selected surface. Consequently, footstep planning can be addressed with a Mixed IntegerProgram (MIP), an elegant but computationally-demanding method, which can make it unsuitable for online planning.We reformulate the MIP into a cardinality problem, then approximate it as a computationally efficient l1-norm minimisation, called SL1M. Moreover, we improve the performance and convergence of SL1M by combining it with a sampling-based root trajectory planner to prune irrelevant surface candidates.Our tests on the humanoid Talos in four representative scenarios show that SL1M always converges faster than MIP. For scenarios when the combinatorial complexity is small (<10surfaces per step), SL1M converges at least two times faster than MIP with no need for pruning. In more complex cases,SL1M converges up to 100 times faster than MIP with the help of pruning. Moreover, pruning can also improve the MIP computation time. The versatility of the framework is shown with additional tests on the quadruped robot ANYmal."
abstract_short = ""
authors = ["Daeun Song, Pierre Fernbach, Thomas Flayols, Andrea Del Prete, Nicolas Mansard, Steve Tonneau, Young J. Kim"]
date = "2020-11-17"
image_preview = "2021_ral_daeun.png"
math = true
publication_types = ["1"]
publication = "*IEEE Robotics and Automation Letters* (under review)"
publication_short = "*IEEE RA-L* (under review)"
selected = false
title = "Solving Footstep Planning as a Feasibility Problem using L1-norm Minimization"
url_code = ""
url_dataset = ""
url_pdf = ""
url_project = ""
url_slides = ""
url_video = "https://youtu.be/3AfBM8K0wts"

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

[header]
image = "2021_ral_daeun.png"
caption = ""

+++

{{< youtube 3AfBM8K0wts >}}
