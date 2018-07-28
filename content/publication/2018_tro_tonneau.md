+++
abstract = "We present a contact planner for complex legged locomotion tasks: standing up, climbing stairs using a handrail, crossing rubble, and getting out of a car. The need for such a planner was shown at the DARPA Robotics Challenge, where such behaviors could not be demonstrated (except for egress). Current planners suffer from their prohibitive algorithmic complexity because they deploy a tree of robot configurations projected in contact with the environment. We tackle this issue by introducing a reduction property: the reachability condition. This condition defines a geometric approximation of the contact manifold, which is of low dimension, presents a Cartesian topology, and can be efficiently sampled and explored. The hard contact planning problem can then be decomposed into two subproblems: first, we plan a path for the root without considering the whole-body configuration, using a sampling-based algorithm; then, we generate a discrete sequence of whole-body configurations in static equilibrium along this path, using a deterministic contact-selection algorithm. The reduction breaks the algorithm complexity encountered in previous works, resulting in the first interactive implementation of a contact planner (open source). While no contact planner has yet been proposed with theoretical completeness, we empirically show the interest of our framework: in a few seconds, with high success rates, we generate complex contact plans for various scenarios and two robots: HRP-2 and HyQ. These plans are validated in dynamic simulations or on the real HRP-2 robot."
abstract_short = ""
authors = ["Steve Tonneau", "Andrea Del Prete", "Julien Pettré", "Chonhyon Park", "Dinesh Manocha", "Nicolas Mansard"]
date = "2018-04-19"
image_preview = ""
math = true
publication_types = ["2"]
publication = "*IEEE Transactions on Robotics*"
publication_short = "*T-Ro*"
selected = false
title = " An Efficient Acyclic Contact Planner for Multiped Robots"
url_code = ""
url_dataset = ""
url_pdf = "https://hal.archives-ouvertes.fr/hal-01267345/document"
url_project = ""
url_slides = ""
url_video = "https://www.youtube.com/watch?v=K3ivZe0AS68"

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

[header]
image = ""
caption = ""
+++

{{< youtube K3ivZe0AS68 >}}