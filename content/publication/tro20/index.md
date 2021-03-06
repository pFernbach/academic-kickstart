+++
title = "C-CROC: Continuous and Convex Resolution of Centroidal dynamic trajectories for legged robots in multi-contact scenarios"
date = 2020-01-29
authors = ["Pierre Fernbach", "Steve Tonneau", "Olivier Stasse", "Justin Carpentier", "Michel Taïx"]
publication_types = ["2"]
abstract = "Synthesizing legged locomotion requires planning one or several steps ahead (literally): when and where, and with which effector should the next contact(s) be created between the robot and the environment? Validating a contact candidate implies \textit{a minima} the resolution of a slow, non-linear optimization problem, to demonstrate that a Center Of Mass (COM) trajectory, compatible with the contact transition constraints, exists. We propose a conservative reformulation of this trajectory generation problem as a convex 3D linear program, CROC. It results from the observation that if the COM trajectory is a polynomial with only one free variable coefficient, the non-linearity of the problem disappears. This has two consequences. On the positive side, in terms of computation times CROC outperforms the state of the art by at least one order of magnitude, and allows to consider interactive applications (with a planning time roughly equal to the motion time). On the negative side, in our experiments our approach finds a majority of the feasible trajectories found by a non-linear solver, but not all of them. Still, we demonstrate that the solution space covered by CROC is large enough to achieve the automated planning of a large variety of locomotion tasks for different robots, demonstrated in simulation and on the real HRP-2 robot, several of which were rarely seen before. Another significant contribution is the introduction of a Bezier curve representation of the problem, which guarantees that the constraints of the COM trajectory are verified continuously, and not only at discrete points as traditionally done. This formulation is lossless, and results in more robust trajectories. It is not restricted to CROC, but could rather be integrated with any method from the state of the art."
selected = "true"
publication = ""
tags = ["Multi contact locomotion ; centroidal dynamics ; Humanoid robots ; legged robots ; Motion planning"]
url_custom = [{name = "View on HAL", url = "https://hal.laas.fr/hal-01894869"}]
url_preprint = "https://hal.laas.fr/hal-01894869/document"
url_video ="https://youtu.be/oKKlShZvcs4"
+++

{{< youtube oKKlShZvcs4 >}}
