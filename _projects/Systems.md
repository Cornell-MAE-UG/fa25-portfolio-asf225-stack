---
layout: project
title: Systems Dissection
description: Control Systems Dissection of a Milk Frother 
technologies: [MATLAB]
image: assets/images/model.png
---

For this project, our team analyzed the system dynamics of a handheld milk frother by modeling its rotational behavior during coast-down. After experimentally capturing the frother’s ramp-down data using high-speed video, my role was to develop the mathematical model and use MATLAB to determine the governing equation of motion. I compared viscous damping, quadratic drag, and mixed damping models by fitting each to the experimental data and evaluating their accuracy using linearization techniques and R² values. Through this analysis, I identified viscous damping as the dominant physical mechanism and extracted key system parameters, including the time constant and the ratio J/b. I then helped translate the model into transfer functions, state-space form, and relevant plots to characterize the frother as a first-order open-loop system. This work strengthened my ability to connect experimental data with analytical modeling, evaluate competing physical models, and use MATLAB to derive and validate dynamic system equations.

Link to Assignment: in [PDF format]({{ "/assets/MAE 3260_ Milk Frothers Final Project.pdf" | relative_url }}).
