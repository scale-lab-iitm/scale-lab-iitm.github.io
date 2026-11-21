---
title: Ongoing Research
---

# {% include icon.html icon="fa-solid fa-flask" %}Ongoing Research

Current projects in the SCaLe Lab, spanning learning-based and adaptive control with applications to fusion plasmas and robotics.

{% include section.html %}

<!--
  To fill in a project, replace the title, the "Team" line, and the description.
  To add a project, copy one <div class="research-app"> ... </div> block.
  Icons: https://fontawesome.com/search?ic=free (e.g. fa-atom, fa-robot, fa-industry, fa-wave-square)
-->

<div class="research-apps">
  <div class="research-app">
    <i class="icon-converging-error" aria-hidden="true"></i>
    <h3>Event-triggered adaptive control in RKHS</h3>
    <p>Adaptive controllers in reproducing kernel Hilbert spaces (RKHS) can handle complex uncertainties with rigorous guarantees, but their computational cost grows with the number of kernel basis functions and the state dimension, which can rule out real-time use. This project develops an event-triggered algorithm that adds and removes basis functions as needed, using vector-valued RKHS and compactly supported kernels. The aim is a controller that keeps the number of active basis functions bounded while guaranteeing convergence of the tracking error; we are also analyzing the time between dictionary updates.</p>
  </div>
  <div class="research-app">
    <i class="fa-solid fa-atom" aria-hidden="true"></i>
    <h3>Safe reinforcement learning for plasma density control</h3>
    <p>Fusion power grows with plasma density, but pushing density too high can trigger instabilities and disruptions that damage reactor-grade tokamaks. This project develops a safe reinforcement learning controller that tracks a target density while the plasma is in a safe range, and switches to prioritizing safety as it approaches a known stability limit. We are training the agent in simulation and testing it in tokamak experiments, with the goal of resolving this performance–safety trade-off in real time and generalizing to scenarios that differ substantially from training.</p>
  </div>
  <div class="research-app">
    <i class="fa-solid fa-atom" aria-hidden="true"></i>
    <h3>Kernel-based adaptive control of fusion fuel density</h3>
    <p>Burning plasmas in reactor-grade tokamaks need precise regulation of the deuterium–tritium (D-T) fuel density, but its evolution is hard to model because of complex particle exchange between the plasma core, the scrape-off layer, and the wall. This project develops a data-driven, nonparametric adaptive controller that treats these unknown nonlinear dynamics as elements of a reproducing kernel Hilbert space (RKHS) and learns them during operation. We are characterizing the stability and performance of the closed-loop system and evaluating the controller in simulations of ITER-relevant scenarios.</p>
  </div>
  <div class="research-app">
    <i class="fa-solid fa-robot" aria-hidden="true"></i>
    <h3>Learning-based control of robotic manipulators</h3>
    <p class="research-app-meta">Description coming soon.</p>
  </div>
</div>

{% include section.html %}

{%
  include button.html
  link="research/past"
  text="Past research"
  icon="fa-solid fa-clock-rotate-left"
%}

{%
  include button.html
  link="research"
  text="Back to Research"
  icon="fa-solid fa-arrow-left"
%}
