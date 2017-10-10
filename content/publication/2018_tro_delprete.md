+++
abstract = "The  ability  to  anticipate  a  fall  is  fundamental  for any  robot  that  has  to  balance.  Currently,  fast  fall-prediction algorithms  only  exist  for  simple  models,  such  as  the  Linear Inverted  Pendulum  Model  (LIPM),  whose  validity  breaks  down in multi-contact scenarios (i.e. when contacts are not limited to a flat ground). This paper presents a fast fall-prediction algorithm based  on  the  point-mass  model,  which  remains  valid  in  multi-contact  scenarios.  The  key  assumption  of  our  algorithm  is  that, in  order  to  come  to  a  stop  without  changing  its  contacts,  a robot only needs to accelerate its center of mass in the direction opposite to its velocity. This assumption allows us to predict the fall by means of a convex optimal control problem, which we solve with  a  fast  custom  algorithm  (less  than  10  ms  of  computation time).  We  validated  the  approach  through  extensive  simulations with the humanoid robot HRP-2 in randomly-sampled scenarios. Comparisons  with  standard  LIPM-based  methods  demonstrate the  superiority  of  our  algorithm  in  predicting  the  fall  of  the robot, when controlled with a state-of-the-art balance controller. This work lays the foundations for the solution of the challenging problem  of  push  recovery  in  multi-contact  scenarios."
abstract_short = ""
authors = ["Andrea Del Prete", "Steve Tonneau", "Nicolas Mansard"]
date = "2018-03-01"
image_preview = ""
math = true
publication_types = ["2"]
publication = "*IEEE Transaction on Robotics* (conditionally accepted)"
publication_short = "*T-Ro* (conditionally accepted)"
selected = false
title = "Zero Step Capturability for Legged Robots in Multi Contact"
url_code = ""
url_dataset = ""
url_pdf = "https://hal.archives-ouvertes.fr/hal-01574687/document"
url_project = ""
url_slides = ""
url_video = "https://youtu.be/WjVcNeMapN8"

#[[url_custom]]
#name = "Custom Link"
#url = "http://www.example.org"

[header]
image = ""
caption = ""
+++

{{< youtube WjVcNeMapN8 >}}