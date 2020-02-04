+++
title = "Motion Planning for an Elastic Rod using Contacts"
date = 2019-09-30
authors = ["Olivier Roussel", "Pierre Fernbach", "Michel Taïx"]
publication_types = ["2"]
abstract = "This paper focuses on the motion planning problem of an extensible elastic rod in collision-free or contact space. The rod is assumed to be handled by grippers either at one or both extremities. Furthermore, during manipulation, the grasped end may change. We show that the use of both quasi-static and dynamic models can be coupled efficiently with sampling-based methods. Sampling directly in the submanifold of static equilibrium and contact-free configurations allows to take advantage of the dynamic model to improve the exploration of the state space. In this way, thanks to the contact information (point, forces, direction, number of contacts), the exploration of the RRT approach can be improved. We present a new RRT-SLIDE algorithm which guides the roadmap extension with a sliding contact mode based on some principles of human reasoning. We show that our approach is probabilistically complete. We also demonstrate the necessity of considering contacts on complex scenarios with several simulation experiments. Besides its performances , our algorithm does not require further tuning phase for a new scenario. Note to Practitioners-This work was done under the industrial project Flecto (ANR-Digital Models). It aims at solving the assembly/disassembly task for a rod while satisfying the elasticity parameters of its material. For industrial applications, the resolution time is a critical point. On the one hand, probabilistic motion planning methods require to efficiently build a roadmap of valid rod configurations. On the other hand, accurate rod modeling implies the use of a simulator based on the finite element method. Nevertheless, the very large size of the roadmap, that leads to a high number of calls to the simulator, is conflicting with the high computational cost of finite-element based simulation. To overcome this problem, one solution is to reduce the number of simulator calls. This can be achieved by sampling the free space with an efficient parameterization and by limiting the use of the simulator to roadmap extension in the free space or in the contact space. We introduce heuristics based on contact information returned by the simulator to reduce significantly the computational time. One of the main advantages of our algorithm is that it does not require any tuning phase for each scenario. Although we do not solve the more general gripper manipulation planning problem, this approach could be used as a first step before computing the motion of the grippers. In the framework of our project, we did not consider disassembling operations implying undoing rod knots. Consequently, we do not take friction into account in our approach. In order to handle knots, it would be necessary to have a physics simulator that could handle friction for deformable rods."
selected = "true"
publication = ""
tags = ["Motion planning ; contact planning ; sliding motion : elastic rod"]
url_custom = [{name = "View on HAL", url = "https://hal.laas.fr/hal-01954894"}]
url_preprint = "https://hal.laas.fr/hal-01954894/document"
+++
