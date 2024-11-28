---
title: Deep learning for haptic force estimation
image: images/forceprediction.jpg
tags:
  - Surgical Robotics
  - Force Sensor

---

### Distal-end force prediction of tendon-sheath mechanisms for flexible endoscopic surgical robots using deep learning

<figure class="figure">
  <img src="https://pheelab.github.io/images/forceprediction.jpg" alt="Force sensor">
</figure>


Accurate haptic feedback is highly challenging for flexible endoscopic surgical robots due to space limitation for sensors on small end-effectors and critical force hysteresis of their tendon-sheath mechanisms (TSMs). This paper proposes a deep learning approach to predicting the distal force of TSMs when manipulating a biological tissue based on only proximal-end measurements. Both Multilayer Perceptron (MLP) and Recurrent Neural Network (RNN) were investigated to study their capabilities of making sequential distal force predictions. The results were compared with those of the conventional modelling approach. It was observed that, when sufficient data was provided for training, RNN achieved the most accurate prediction (RMSE=0.0219N) in experiments with constant system velocity. The effects of insufficient training data, varying system velocity and irregular motion trajectories on the performance of RNN were further studied. Notably, RNN could precisely identify the current system phase in the force hysteresis profile and can be applied to TSMs with realistic non-periodic movement such as manual manipulation trajectory (RSME=0.2287N). The proposed approach can be applied to any TSM-driven robotic systems for accurate haptic feedback without requiring sensors at the distal ends of the robots.


### Related Pubulication:

{: .box-note}
**Paper:** Li, Xiaoguo, et al. "Distal-end force prediction of tendon-sheath mechanisms for flexible endoscopic surgical robots using deep learning."  [ Mechanism and Machine Theory 134 (2019): 323-337.](https://doi.org/10.1016/j.mechmachtheory.2018.12.035)

--- 
*(c)  Pheelab. All rights reserved.*
