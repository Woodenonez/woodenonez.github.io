---
layout: single
# classes: wide
permalink: /projects/
author_profile: false
title: "Projects"
toc: true
toc_label: "On this page"
toc_icon: "list"
toc_sticky: true
---

## RAIN
{: .project-title }

Cloud Robotics - Ongoing

## DRL-MPC
{: .project-title }

DRL-Boosted Optimal Control for Flexible Navigation in Complex Environments
### Introduction
This side project proposes an efficient approach to real-time collision-free navigation for mobile robots in complex environments (with non-convex obstacles). By integrating deep reinforcement learning with model predictive control, the aim is to achieve both collision avoidance and computational efficiency. The methodology begins with training a preliminary agent using deep reinforcement learning (DQN and DDPG), enabling it to generate actions for next time steps. Instead of executing these actions, a reference trajectory is generated based on them, which avoids obstacles present on the original reference path. Subsequently, this local trajectory is employed within an MPC trajectory-tracking framework to provide collision-free guidance for the mobile robot.

For multi-agent cases, decentralized training with decentralized execution (DTDE) is used for DRL agents, and distributed MPC is conducted for flexibility and scalability.
### Information
This is a side project initiated by me and extended to a larger reseacher project involving more new reseachers.

### Reference(s): 
1. [IEEE CASE](https://ieeexplore.ieee.org/document/10260515)
2. [IEEE IROS](https://ieeexplore.ieee.org/document/10801434)

## FON-AMR
{: .project-title }

Future-Oriented Navigation for Autonomous Mobile Robots
### Introduction
As industrial environments become more dynamic and collaborative, Autonomous Mobile Robots (AMRs) are being deployed to work alongside humans. While hybrid human-robot settings offer improved efficiency and adaptability, they also challenge safety due to human behavior's inherent unpredictability. This project is motivated by the goal of enabling AMRs to anticipate and react to dynamic environments by integrating learning-based prediction with optimization-based control. Specifically, it focuses on safer and more efficient future-oriented navigation, i.e., decision-making that incorporates predictive information about the near future.
### Information
This is a five-year research project as the main topic of my PhD study. This project is supported by several larger research projects: ViMCoR (2019-2021), AIHURO (VINNOVA, 2023-2025), etc. The main collaborator is Volvo GTO. This project is also in collaboration with / founded by Chalmers AI Research Centre (CHAIR) and AstraZeneca.

### Reference(s): 
1. [PhD Thesis](https://research.chalmers.se/en/publication/545958)
2. [IEEE RA-L](https://ieeexplore.ieee.org/document/11021381) ([arXiv](https://arxiv.org/abs/2505.00237v1))


<!-- ### Review activities

SII (AE, 2026), IROS (2025), Mechatronics (2025), RA-L(2024), T-HRI(2024), ESWA (2024), ECC (2024), CASE (2024, 2023), UR (2022).

```
Template for review:
1. Short summarization (motivation/background, content, method, contribution)
2. General comments (novelty, clearness, rigour, impact, major problems?)
3. Specific problems in each section
4. Data/experiment/evaluation problems
5. Figure/table/equation problems
6. Others
``` -->