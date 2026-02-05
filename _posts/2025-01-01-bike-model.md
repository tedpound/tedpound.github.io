---
layout: article
title: "Bike System Model"
tags: [project]
categories: [projects]
cover: /assets/website-pics/bike-model/bike-model-icon.png
aside: false
show_date: false
show_tags: false
license: false
show_subscribe: false
---

<div style="text-align: center; margin-bottom: 2rem; padding: 0 0.5rem;">
  <img src="/assets/website-pics/bike-model/model-math.png" alt="Bike Model Mathematics" style="width: 100%;" />
</div>

<div style="padding: 0 0.5rem; margin-bottom: 1rem;">
This project focused on modeling and analyzing the dynamics of a ground vehicle using a nonlinear state-space framework. I developed a kinematic model with steering angle and longitudinal acceleration as control inputs and vehicle position, velocity, and heading as system states. The model captured nonlinear behavior through trigonometric relationships and velocity-dependent terms commonly used in mobile robot and autonomous vehicle modeling. I then derived a linearized version of the system to evaluate local behavior around an operating point and assess suitability for control design.
</div>

<div style="text-align: center; margin-bottom: 2rem; padding: 0 0.5rem;">
  <img src="/assets/website-pics/bike-model/plots.png" alt="Model Comparison Plots" style="width: 100%;" />
</div>

<div style="padding: 0 0.5rem; margin-bottom: 1rem;">
A key challenge was understanding the limits of linearization for control applications. The linear model provided accurate predictions near equilibrium but diverged as inputs increased or operating conditions changed. I compared nonlinear and linear responses through time-domain simulation in MATLAB and analyzed how modeling assumptions affected tracking and stability. This project strengthened my understanding of state-space modeling, linearization, and the tradeoffs involved when applying control techniques to nonlinear robotic systems.
</div>
