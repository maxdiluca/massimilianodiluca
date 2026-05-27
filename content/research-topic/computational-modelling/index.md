---
title: Computational Modelling
subtitle: Formal models of perception, timing, movement, and interaction
topic_label: computational modelling
topic_tag: computational modelling
key_questions:
  - How can formal models explain perceptual decisions, cue integration, timing, and movement?
  - Which assumptions about uncertainty, delay, priors, and evidence accumulation predict behaviour?
  - How can simulation and data analysis support haptic rendering, XR datasets, and experimental design?
  - How do models connect basic perceptual theory with usable interactive systems?
funding:
  - EXPLORA
  - Input Vault
  - XR Text Trove
  - "ARME: Augmented Reality Music Ensemble"
  - "Taking the rough with the smooth: aging effects on tactile surface texture perception"
  - Haptic perception of softness
  - Softness with pinch grasp
portfolio:
  - xrtexttrove
  - locomotionvault
  - codedelay
  - prendosim
  - virtuoso-strings
  - agingtouch
  - skmethod
figure:
  image: /media/research-topic/computational-modelling.png
  alt: Computational modelling and simulation figure
  caption: Computational models connect perceptual theory with simulation, prediction, datasets, and interactive systems.
related_labels:
  - bayesian model
  - kalman filter
  - signal processing
  - simulation
  - data analysis
  - diffusion model
  - linear regression model
  - deformable models
  - movement analysis
  - kinematics
related_topics:
  - psychophysics
  - multisensory-perception
  - temporal-perception
  - extended-reality-virtual-reality
---

Computational modelling is used to explain perceptual decisions, predict behaviour, and guide the design of interactive systems. The work includes Bayesian cue integration, Kalman filtering, signal processing, simulation, data-driven haptic rendering, psychometric modelling, movement analysis, and machine learning.

The same perspective also shapes my teaching in [Mind, Brain, and Models](/#teaching). In that module, students use computational models as working theories: they simulate perceptual and cognitive systems, compare alternative explanations quantitatively, and learn how assumptions about uncertainty, evidence, prior knowledge, and decision rules change the behaviour a model predicts.

Many of the research models address uncertainty. Sensory signals are noisy, delayed, context-dependent, and often only indirectly related to the property being judged. Formal models help explain how people combine evidence across modalities, how expectations shape perceived timing, why visual-haptic conflicts change perceived stiffness, and how tactile information may be encoded by skin and mechanoreceptor systems.

### Model families

The computational modelling strand spans several complementary approaches. Bayesian and statistically optimal models are used to ask how observers should combine uncertain evidence, and where human behaviour follows or departs from those predictions. These models are especially useful for multisensory perception, visual-haptic integration, body ownership, depth, timing, and causal inference.

Dynamic models describe how perception and action unfold over time. Kalman-filter and feedback-correction models capture how people update predictions in response to changing sensory evidence, including musical synchronisation and temporally structured environments. Evidence-accumulation and diffusion-style models connect perceptual uncertainty to response time, accuracy, and speed-accuracy trade-offs.

Simulation models make hidden mechanisms explicit. In haptics and touch, simulations of skin, mechanoreceptors, tactile ageing, surface contact, vibration, and compliance help link physical interaction to the signals available for perception. In movement research, kinematic models and analysis pipelines describe trajectories, biological motion, grasping, locomotion, and the timing of coordinated action.

Data-driven and signal-processing models support the translation of perceptual knowledge into interactive systems. They are used to analyse timing accuracy, extract meaningful structure from XR datasets, transform touch signals into responsive haptic or auditory feedback, and design perceptually grounded interaction techniques for VR, AR, and wearable devices.

### From models to experiments

Models are most useful when they make contact with behaviour. A model can generate a predicted psychometric function, estimate a point of subjective equality, describe a just-noticeable difference, predict a response-time distribution, or identify which variables should matter in a new experiment. This makes modelling a practical part of experimental design rather than a separate post-hoc explanation.

This approach also makes disagreement productive. When a model fails, the failure can reveal a missing prior, an incorrect noise assumption, an unmodelled delay, a change in strategy, or a perceptual cue that the experiment did not explicitly control. The goal is not simply to fit data, but to use models to sharpen the questions asked by psychophysics, neuroscience, HCI, haptics, and XR research.

The modelling strand also supports open resources and technology translation. It underpins datasets and catalogues for XR interaction, tools for timing and psychometric analysis, models of musical synchronisation, simulations of tactile ageing, and methods for turning perceptual knowledge into haptic rendering, VR measurement, and human-machine interaction systems.
