---
layout: page
title: Projects
permalink: /projects/
---

**Current Research Projects**: 


### Research Direction 1: Chip HW/SW Co-Design for AI
Funding: NSF, DoD and Facebook\
Members: Marina Neseem, Ahmed Agiza

**Project 3.1: Adaptive Neural Networks for Embedded Devices**: Embedded systems are constrained in their resources (e.g., memory and power), and as a result, it is difficult to deploy large Neural Networks (NNs) on them. We tackle this problem by developing adaptive NNs techniques that scale the amount of computational needs in the NN depending on the accuracy needs. We have explored adaptive operation for the channels in a NNs, as well as adaptive ensemble processing. With the advancement in augmented reality and smart glasses, object detection became an essential task for edge devices. However, STOA object detectors have large compute and memory footprints which challenges their deployment on edge devices. In recent work, we have explored leveraging the prior knowledge about the probabilities that different object categories can occur jointly to increase the efficiency of object detection models. Her results shows 25% reduction in energy and memory footprint with a negligible loss in accuracy.

**Project 3.2: End-to-End Efficient Processing for Wearable Devices**: Wearable devices have strict power and memory limitations. As a result, there is a need to optimize the power consumption on those devices without sacrificing the accuracy. In [AdaSense](https://ieeexplore.ieee.org/document/9218568), we built a sensing, feature extraction and classification co-optimized framework for Human Activity Recognition. AdaSense dynamically adjusts the sampling freuency of the sensor based on the user activity, which reduces the power consumption by up to 69%. Beyond Human Activity Recognition, the idea of dynamic sampling used in AdaSense can be applied to other applications involving different biometric sensors, cameras, etc.

**Project 3.3: Efficient ML Processing for Biometric Security**: Applications of Fully Convolutional Networks (FCN) in iris segmentation have shown promising advances. For mobile and embedded systems, a significant challenge is that the proposed FCN architectures are extremely computationally demanding. In this project, we propose a resource-efficient, end-to-end iris recognition flow, which consists of FCN-based segmentation, contour fitting, followed by Daugman normalization and encoding. To attain accurate and efficient FCN models, we propose a three-step SW/HW co-design methodology consisting of FCN architectural exploration, precision quantization, and hardware acceleration.

--- 


### Research Direction 2: Energy-Efficient and Sustainable Computing
Funding: NSF and DoD\
Members:  Jingxiao Ma, Marina Neseem
Collaborators: Ayse Coskun @ BU

**Project 1.1: Approximate Logic Synthesis**: Approximate logic synthesis (ALS) is the process of synthesizing logic-level cells in the manner of approximate computing, which offers benefits in hardware metrics, such as design area and power consumption, by relaxing the requirement for full accuracy. In BLASYS project, we aims to generate approximate designs of arbitrary input circuit by using Boolean Matrix Factorization. Truth table of the input circuit is factorized into two smaller matrices, which are then synthesized and combined as approximate circuit. This idea is further extended into RunCALS, which designs runtime configurable circuits with the capability of restoring 100% accuracy.  Furthermore, logic synthesis requires extensive tuning of the synthesis optimization flow where the quality of results (QoR) depends on the sequence of optimizations used. Efficient design space exploration is challenging due to the exponential number of possible optimization permutations. In [DRILLS](https://github.com/scale-lab/DRiLLS), we model the logic synthesis optimization problem as an MDP (Markov Decision Process), and used Reinforcement Learning to provide a sequence of optimization commands that achieves outperforming QoR.

**Project 1.2: Approximate Arithmetic Units**: For arithmetic circuit building blocks, we are investigating approximate units for basic building blocks, such as adders, multipliers and dividers. We proposed DRUM, which is a novel approxi- mate multiplier with an unbiased dynamic-range selection scheme.  DRUM has the unique property that it has an unbiased error distribution, which leads to lower computational errors in real applications because errors cancel each other out as the multiplier is used repeatedly for accumulated computations. We extended our dynamic range selection idea to devise approximate dividers that dynamically select the most relevant bits of each of the division operands.  Both DRUM and our divider enable designers to arbitrarily trade-off accuracy for power and area savings during the design process based on their accuracy requirements. We are currently investigate approximate design for multi-operand adders typically using neuran networks.

**Project 1.3: Power/Thermal Management for Mobile Processors:** Mobile devices have become an essential part of daily life with the increased computing capabilities and features. However, their limited cooling capabilities makes thermal management a critical factor in determining performance limits. Additionally, mobile devices are battery powered devices, which raises power and battery management challenges. We have been working on proposing  control techniques using modeling and machine learning to manage the different sources of power and thermal emergencies in a mobile SoC, in order to provide the best performance while respecting the  specifications. Furthermore, we are working on  battery lifetime management technique that coordinate the DVFS settings of the CPU and GPU in a mobile SoC to improve the user experience by maximizing the performance while meeting the user desired battery lifetime. Our lab, in collaboration with the PEAC lab, has developed thermal modeling techniques for ICs with emerging cooling systems, including thermoelectric coolers, liquid cooling, and micro-evaporator chambers.  Enabled by parallel computing methods, our tool, PACT, performs a large range of thermal analysis techniques in very fast runtimes.

**Project 1.4: Power Management and Capping for Datacenters:** Modern servers typically use multiple high-end CPUs and GPUs causing the power per server to add up to more than 500-100W.  Furthermore, the total power consumption of servers can add up to mega Watts of power in a typical datacenter.  In this project, we investigate novel power capping techniques for servers with CPUs and GPUs that can enable servers to maximizer performance with power cap limits. In addition we devise decentralized power capping methods for large datacenters to reduce the lag time between the introduction and application of the power cap. More recently, we focus on power management for servers that run machine learning workloads. Machine learning (ML) workloads enable a new class of power management techniques to trade-off latency, power and Quality of Results (QoR). We are currently investigating management techniques that use DVFS, precision, batch sizes, workload co-location to achieve target performance, power, and QoR.

---

### Research Direction 3: Molecular Computing
Funding: DARPA and NSF\
Members: Ahmed Agiza\
Collaborators: Jacob Rosenstein, Brenda Rubenstein, Eunsuk Kim, Christopher Rose

**Project 2.1:** In this project we are working on using molecules and chemical reactions to encode and process information. While DNA has been the stereotypical molecule, the molecular universe has millions of other molecules that can offer advantages over DNA. We are exploring the use if multi-component molecular systems (e.g., Ugi compounds) to store information at much higher density that DNA. We are also exploring the use of phenols to encode data and acetylation reactions to conduct parallel arithmetic operations.  Furthermore, we are exploring the use of auto-catalytic reactions to perform non-linear functions, such as thresholding. Using our proposed molecular systems, we have demonstrated *in chemico* image processing and classification systems.

--- 


### Research Direction 4: Thermal/Power Modeling and Management for Mobile and Servers
Funding: NSF and Samsung\
Members: NA \
Collaborators: Ayse Coskun and M. Syed Nabavinejad

 

----
