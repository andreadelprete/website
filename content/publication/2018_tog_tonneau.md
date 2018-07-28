+++
abstract = "Synthesizing motions for legged characters in arbitrary environments is a long-standing problem that has recently received a lot of attention from the computer graphics community. We tackle this problem with a procedural approach that is generic, fully automatic and independent from motion capture data. The main contribution of this paper is a point-mass-model-based method to synthesize Center Of Mass trajectories. These trajectories are then used to generate the whole-body motion of the character. The use of a point mass model results in physically inconsistent motions and joint limit violations when mapped back to a full- body motion. We mitigate these issues through the use of a novel formulation of the kinematic constraints which allows us to generate a quasi-static Center Of Mass trajectory, in a way that is both user-friendly and computationally efficient. We also show that the quasi-static constraint can be relaxed to generate motions usable for computer animation, at the cost of a moderate violation of the dynamic constraints. Our method was integrated in our open-source contact planner and tested with different scenarios - some never addressed before- featuring legged characters performing non-gaited motions in cluttered environments. The computational efficiency of our trajectory generation algorithm (under one ms to compute one second of trajectory) enables us to synthesize motions in a few seconds, one order of magnitude faster than state-of-the-art methods. Although our method is empirically able to synthesize collision-free motions, the formal handling of environmental constraints is not part of the proposed method, and left for future work."
abstract_short = ""
authors = ["Steve Tonneau", "Pierre Fernbach", "Andrea Del Prete", "Julien Pettré", "Nicolas Mansard"]
date = "2018-XX-XX"
image_preview = ""
math = true
publication_types = ["2"]
publication = "*IEEE Transactions on Graphics*"
publication_short = "*ToG*"
selected = false
title = "2PAC: Two Point Attractors for Center of Mass Trajectories in Multi Contact Scenarios"
url_code = ""
url_dataset = ""
url_pdf = "https://hal.archives-ouvertes.fr/hal-01609055/document"
url_project = ""
url_slides = ""
url_video = "https://www.youtube.com/watch?v=PvOoMSlKoxE"

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

[header]
image = ""
caption = ""
+++

{{< youtube PvOoMSlKoxE >}}