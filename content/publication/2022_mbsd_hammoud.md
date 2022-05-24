+++
abstract = "The simulation of multibody systems with frictional contacts is a fundamental tool for many fields, such as robotics, computer graphics, and mechanics. Hard frictional contacts are particularly troublesome to simulate because they make differential equations stiff, calling for computationally demanding implicit integration schemes. We suggest to tackle this issue by using exponential integrators, a long-standing class of integration schemes (first introduced in the 1960s) that in recent years has enjoyed a resurgence of interest. This scheme can be applied to multibody systems subject to stiff viscoelastic contacts, leading to integration errors similar to implicit Euler, but at much lower computational costs (between 2 to 100 times faster). In our tests with quadruped and biped robots, our method demonstrated a stable behavior with large time steps (10 ms) and stiff contacts (10^5 N/m). Its excellent properties, especially for fast and coarse simulations, make it a valuable candidate for many applications in robotics, such as simulation, model predictive control, reinforcement learning, and controller design."
abstract_short = ""
authors = ["Bilal Hammoud, Luca Olivieri, Ludovic Righetti, Justin Carpentier, Andrea Del Prete"]
date = "2022-04-11"
image_preview = "2021_ral_hammoud.png"
math = true
publication_types = ["2"]
publication = "*Multi Body System Dynamics*"
publication_short = "*MBSD*"
selected = false
title = "Exponential Integration for Efficient and Accurate Multibody Simulation with Stiff Viscoelastic Contacts"
url_code = "https://github.com/andreadelprete/consim"
url_dataset = ""
url_pdf = "https://arxiv.org/pdf/2101.06846.pdf"
url_project = ""
url_slides = ""
url_video = "https://youtu.be/GaXoBuVczEw"

[[url_custom]]
name = "Springer"
url = "https://link.springer.com/article/10.1007/s11044-022-09818-z"

[header]
image = "2021_ral_hammoud.png"
caption = ""

+++

{{< youtube GaXoBuVczEw >}}