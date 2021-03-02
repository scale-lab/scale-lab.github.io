---
layout: page
title: Projects
permalink: /projects/
---

**Current Research Projects**: 

![](approx.png)

### Research Direction 1: Approximate and scalable computing for energy efficiency
Funding: NSF and DoD\
Members:  Jingxiao Ma, Marina Neseem, Andrew Duncombe \

**Project 1.1: Approximate Logic Synthesis**: Approximate logic synthesis (ALS) is the process of synthesizing logic-level cells in the manner of approximate computing, which offers benefits in hardware metrics, such as design area and power consumption, by relaxing the requirement for full accuracy. In BLASYS project, we aims to generate approximate designs of arbitrary input circuit by using Boolean Matrix Factorization. Truth table of the input circuit is factorized into two smaller matrices, which are then synthesized and combined as approximate circuit. This idea is further extended into RunCALS, which designs runtime configurable circuits with the capability of restoring 100% accuracy.

**Project 1.2: Logic Synthesis Optimization**: Logic synthesis requires extensive tuning of the synthesis optimization flow where the quality of results (QoR) depends on the sequence of optimizations used. Efficient design space exploration is challenging due to the exponential number of possible optimization permutations. In [this project](https://github.com/scale-lab/DRiLLS), Abdelrahman modeled the logic synthesis optimization problem as an MDP (Markov Decision Process), and used Reinforcement Learning to provide a sequence of optimization commands that achieves outperforming QoR.

**Project 1.3: Spiking Neural Networks**: Spiking neural networks (SNNs) are a recently developed neural network architecture that aims to emulate the brain in order to improve energy efficiency. SNNs are inherently resilient to even computation errors, which implies that approximate computing methods may be an effective strategy to improving performance. In this project, we are designing a novel approximate SNN neuron to improve the efficiency of the spiking neuron computation by using adder tree approximations and a novel weight summation unit.

---

![](chem.png)

### Research Direction 2: Emerging molecular computing paradigms
Funding: DARPA and NSF\
Members: Ahmed Agiza\
Collaborators: Jacob Rosenstein, Brenda Rubenstein, Eunsuk Kim, Christopher Rose\

**Project 2.1:** In this project we are working on using molecules and chemical reactions to encode and process information. While DNA has been the stereotypical molecule, the molecular universe has millions of other molecules that can offer advantages over DNA. We are exploring the use if multi-component molecular systems (e.g., Ugi compounds) to store information at much higher density that DNA. We are also exploring the use of phenols to encode data and acetylation reactions to conduct parallel arithmetic operations.  Furthermore, we are exploring the use of auto-catalytic reactions to perform non-linear functions, such as thresholding. Using our proposed molecular systems, we have demonstrated *in chemico* image processing and classification systems.

--- 
![](AI.png)

### Efficient machine learning processing for resource-constrained embedded and wearable devices
Funding: NSF, DoD and Facebook\
Members: Abdelrahman Hosny, Marina Neseem, Ahmed Agiza\

**Adaptive Context-Aware Object Detection for Embedded Devices**: With the advancement in augmented reality and smart glasses, object detection became an essential task for edge devices. However, STOA object detectors have large compute and memory footprints which challenges their deployment on edge devices. In recent work, Marina has explored leveraging the prior knowledge about the probabilities that different object categories can occur jointly to increase the efficiency of object detection models. Her results shows 25% reduction in energy and memory footprint with a negligible loss in accuracy.

**Low-Power Sensing for Human Activity Recognition on Wearable Devices**: Wearable devices have strict power and memory limitations. As a result, there is a need to optimize the power consumption on those devices without sacrificing the accuracy. In [AdaSense](https://ieeexplore.ieee.org/document/9218568), Marina built a sensing, feature extraction and classification co-optimized framework for Human Activity Recognition. AdaSense dynamically adjusts the sampling freuency of the sensor based on the user activity, which reduces the power consumption by up to 69%. Beyond Human Activity Recognition, the idea of dynamic sampling used in AdaSense can be applied to other applications involving different biometric sensors, cameras, etc.


--- 
![](hotspot.png)

### Thermal & power sensing, modeling and management for mobile SoCs
Funding: NSF and Samsung\
Members: Sofiane Chetoui\
Collaborators: Ayse Coskun\

Mobile devices have become an essential part of daily life with the increased computing capabilities and features. However, their limited cooling capabilities makes thermal management a critical factor in determining performance limits. Additionally, mobile devices are battery powered devices, which raises power and battery management challenges. We have been working on proposing  control techniques using modeling and machine learning to manage the different sources of power and thermal emergencies, in order to provide the best performance while respecting the phone specifications. Furthermore, he proposed a workload- and user-aware batterry lifetime management technique to improve the user experience by maximizing the performance while meeting the user desired battery lifetime.

----
