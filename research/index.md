---
title: Research
nav:
  order: 1
  tooltip: Core research and complex-system applications
  # drop-down sub-menu; each link can point to a section (#id) or a separate page
  children:
    - title: Overview
      link: research/
    - title: Ongoing research
      link: research/ongoing/
    - title: Past research
      link: research/past/
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

{% capture overview-alt %}Core research at the intersection of Control & Estimation and Approximation & Learning, applied to complex systems: plasmas, structures, and robotics.{% endcapture %}

<div class="figure-plain show-light">
{% include figure.html image="images/research-overview.png" width="450px" alt=overview-alt %}
</div>
<div class="figure-plain show-dark">
{% include figure.html image="images/research-overview-dark.png" width="450px" alt=overview-alt %}
</div>

Our research lies at the intersection of control theory, estimation, and machine learning. We develop methods for nonlinear dynamical systems with rigorous guarantees, and apply them to complex engineering systems.

{% include section.html %}

## Core research

### Control & Estimation

We study estimation and control of systems governed by nonlinear differential equations in the presence of uncertainties, with rigorous guarantees.

### Approximation & Learning

We leverage tools from approximation and learning theory, such as reproducing kernel Hilbert spaces, for dynamical system uncertainty approximation with provable convergence.

### Where they meet

Our core research sits at the overlap: learning-based controllers and estimators that retain provable stability and convergence guarantees.

<div class="research-apps">
  <div class="research-app">
    <i class="icon-converging-error" aria-hidden="true"></i>
    <h3>Kernel-based adaptive control</h3>
    <p>Adaptive controllers that learn unknown nonlinearities online in reproducing kernel Hilbert spaces, with guaranteed convergence of the tracking error.</p>
  </div>
  <div class="research-app">
    <i class="icon-sum-of-kernels" aria-hidden="true"></i>
    <h3>Function estimation in native spaces</h3>
    <p>Learning unknown functions and operators from trajectory data, with conditions for convergence and rates of approximation.</p>
  </div>
</div>

{% include section.html %}

## Complex systems

We bring these methods to complex engineering systems, where nonlinear dynamics, uncertainty, and limited actuation make control challenging.

<div class="research-apps" data-cols="3">
  <div class="research-app">
    <i class="fa-solid fa-atom" aria-hidden="true"></i>
    <h3>Plasmas</h3>
    <p>Control of fusion plasmas in tokamaks, from density and profile regulation to disruption avoidance.</p>
  </div>
  <div class="research-app">
    <i class="fa-solid fa-robot" aria-hidden="true"></i>
    <h3>Robotics</h3>
    <p>Learning-based control of robotic systems with stability and safety guarantees.</p>
  </div>
  <div class="research-app">
    <i class="fa-solid fa-wave-square" aria-hidden="true"></i>
    <h3>Structures</h3>
    <p>Modeling and estimation of piezoelectric and smart-material structures for vibration attenuation.</p>
  </div>
</div>

{% include section.html %}

## Our projects

See what the lab is working on now, and the earlier research it builds on.

{%
  include button.html
  link="research/ongoing"
  text="Ongoing research"
  icon="fa-solid fa-flask"
%}

{%
  include button.html
  link="research/past"
  text="Past research"
  icon="fa-solid fa-clock-rotate-left"
%}

{% include section.html %}

## Working with us

**Students:** Interested in these problems? See the open positions page for current opportunities and how to get in touch.

**Collaborators:** We welcome collaborations with researchers in academia, national labs and industry on control, estimation, and learning for complex systems. Please reach out through the contact page.

{%
  include button.html
  link="positions"
  text="Open positions"
  icon="fa-solid fa-user-plus"
%}

{%
  include button.html
  link="contact"
  text="Contact"
  icon="fa-regular fa-envelope"
%}

{%
  include button.html
  link="publications"
  text="Read the publications"
  icon="fa-solid fa-scroll"
%}
