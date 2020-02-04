+++
title = "Learning How to Walk: Warm-starting Optimal Control Solver with Memory of Motion"
date = 2020-01-31
authors = ["Teguh Santoso Lembono", "Carlos Mastalli", "Pierre Fernbach", "Nicolas Mansard", "Sylvain Calinon"]
abstract = "In this paper, we propose a framework to build a memory of motion to warm-start an optimal control solver for the locomotion task of the humanoid robot Talos. We use HPP Loco3D, a versatile locomotion planner, to generate offline a set of dynamically consistent whole-body trajectory to be stored as the memory of motion. The learning problem is formulated as a regression problem to predict a single-step motion given the desired contact locations, which is then used as building block for multi-step motions. The predicted trajectory is then used as warm-starts for the fast optimal control solver Crocoddyl. We have shown that the approach manages to reduce the required number of iterations to reach the convergence from ∼9.5 to only ∼3.0 iterations for the single-step motion and from ∼6.2 to ∼4.5 iterations for the multi-step motion, while maintaining the solution's quality. "
publication_types = ["1"]
selected = "true"
publication = "*2020 IEEE International Conference on Robotics and Automation*"
url_custom = [{name = "View on arXiv", url = "https://arxiv.org/abs/2001.11751"}]
url_pdf = "https://arxiv.org/pdf/2001.11751.pdf"
+++

