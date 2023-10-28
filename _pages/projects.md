---
permalink: /projects/
title: "Projects"
---

## [Multiclass Semantic Segmentation of Urban Scenery: Can CBAM or Attention U-Net Unmask What Classical U-Net Cannot?](https://github.com/amagzari/Cityscapes-Semantic-Segmentation)

Understanding urban scenery is critical in a number of areas, the most common of which is autonomous driving. Semantic segmentation specifically is the appropriate task in achieving this purpose as it would allow the conversion of urban scenes into specific regions, each belonging to a particular class (pedestrian, vehicle, traffic sign, etc.). U-Net is a convolutional network that was proposed for biomedical image segmentation. The initial idea behind this paper was to conduct semantic segmentation on the Cityscapes dataset using the classical U-Net, and attempt to ameliorate its performance either by incorporating a Convolutional Block Attention Module (CBAM) or implementing the Attention U-Net architecture, proposed in *Learning Where to Look for the Pancreas*. The experiments show that the three aforementioned network variations do not result in a significant performance improvement. This paper details the methodology and results supporting this statement. 

## [Attribution of Animated Images: The CNN-DCT-Mask Model](/files/attribution.pdf) 

Our purpose is to develop deep learning models to detect whether images are human-created or AI-generated, and to attribute AI-generated images with the names of their generation models. We choose animated-based images as the category of our focus due to the robust ecosystem of talented and engaged artists who relentlessly create new art pieces in this style by hand. The propensity towards sharing images online pioneered by this community provides us with a robust set of hand-drawn and AI-generated images to conduct our testing. The enthusiasm shown by this community in developing open-source models based on the latest published techniques also provides us with methods to generate novel images with which we conduct our tests. This document will explore our techniques with the proposed network CNN-DCT-Mask and findings regarding the attribution of AI-generated images and distinguishing them from those created by human artists.

## [A Java-built Reinforcement Learning Agent in Robocode](/files/robocode.pdf) 

This project implements both on-policy (Sarsa) and off-policy (Q-learning) temporal difference control algorithms to populate a lookup table where several state-action pairs correspond to a specific q-value. The agent was able to achieve a winning rate of 85% after playing 2500 rounds.

## [XOR Function Approximator](/files/robocode.pdf) 

This titorial covers the basic mathematical operations of a neural network, and convergence improvement obtained when using bipolar representation and momentum.