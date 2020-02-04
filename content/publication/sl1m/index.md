+++
title = "SL1M: Sparse L1-norm Minimization for contact planning on uneven terrain"
date = 2019-09-01
authors = ["Steve Tonneau","Daeun Song", "Pierre Fernbach", "Nicolas Mansard", "Michel Taïx", "Andrea Del Prete"]
publication_types = ["1"]
abstract = " We present a novel method for computing centroidal dynamic trajectories in multi-contact planning context. With dynamic motion it is necessary to respect kinematic and dynamic constraints during the contact planning step. Verifying the feasibility of a transition between contacts increase the success rate of the motion generation along the planned contacts. Our approach is based on a conservative but convex reformulation of the problem where we represent the center of mass trajectory as a Bezier curve, with control points constrained by the initial and final states and one free control point. Thanks to the convexity of this formulation, we can solve it efficiently with a Linear Program of low dimension. We use this LP as a feasibility criterion to test the contact transition candidates during multi-contact planning. By incorporating this criterion in an existing sampling-based contact planner, we are able to produce more robust contact sequences. We illustrate this application on various multi-contact scenarios. We also show that we can compute valuable initial guess, used to warm-start non-linear solvers for motion generation methods. This method could also be used for the 0 and 1-Step capturability problem. "
selected = "false"
publication = "*2020 IEEE International Conference on Robotics and Automation*"
url_custom = [{name = "View on HAL", url = "https://hal.laas.fr/hal-02293234"}]
url_pdf = "https://hal.archives-ouvertes.fr/hal-02293234/document"
url_video = "https://youtu.be/gOQHI-YlOi0"
+++
{{< youtube gOQHI-YlOi0 >}}
