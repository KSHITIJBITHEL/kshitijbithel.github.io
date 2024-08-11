---
layout: page
title: RL Based Slosh Control
description: B.Tech. Final Yr. Project
img: assets/img/project_1.gif
importance: 1
category: work
---

Summary : 
* Started by tuning hyperparameters of STC controller using RL in numerical simulations, surpassed the SOTA results
* Secured a grant from Artpark @ IISc Bangalore to realize the research on hardware 
* Developed a Hardware AGV prototype with following features 
    * 4 wheel holonomic meccanum drive 
    * Localisation using fusion of 2 perpendicular single point lidars and an IMU
    * PID based path tracking
    * Fuzzy based velocity controller
    * Capacitance based slosh meeasurement 
* Modelled the hardware AGV prototype using simple pendulum analogy 
    * Estimated the parameters using translational excitation and quick stop strategy 
* Used the estimated model implement 2nd order Sliding mode controller using Super Twisting Algorithm on the hardware.
* Used the estimated model to train RL agent to optimise STC parameters in simulation and applied the learned parameters to the hardware
* Used the estimated model to numerically train DDPG based model-free controller in simulation
* Applied the trained model-free controller on the hardware and fine-tuned its hyperparameters on hardware for some episodes  
* Received the Singhal’s Tech for society award for most innovative, impactful and commercially viable bachelor’s thesis with a cash prize of 50k     

<br>
Here you can find a video(mid-term review) of us explaining the task
<iframe width="560" height="315" src="https://www.youtube.com/embed/agWiQ-R_Qsw" frameborder="0" allowfullscreen></iframe>

<br><br>
Also, for more details, please check out the final [thesis](https://kshitijbithel.github.io/assets/pdf/Bachelors_Thesis.pdf)