---
title: "Dual-Path Beat Tracking: Combining Temporal Convolutional Networks and Transformers in Parallel"
collection: publications
category: manuscripts
permalink: bt
excerpt: 'Parallel TCN–Transformer architecture for temporal event detection in audio. TCN handles local temporal patterns with low complexity; Transformer captures long-range sequence dependencies. Combined model matches state-of-the-art beat tracking accuracy with fewer trainable parameters and no data augmentation.'
date: 17 December 2024
venue: 'Applied Sciences, MDPI'
---

Detecting temporal events in audio requires models that capture both fine-grained local patterns and long-range sequential dependencies. Temporal Convolutional Networks (TCNs), via dilated convolutions, efficiently model local structure. Transformers excel at global sequence modelling. This work combines them in a dual-path parallel architecture for beat tracking, where each branch specialises without interference.

![Beat](/https://static.wixstatic.com/media/ba3be5_b20eff6fe9f04f0189a3ddb4ebba6d94~mv2.png/v1/crop/x_0,y_0,w_512,h_512,q_85,enc_avif,quality_auto/ba3be5_b20eff6fe9f04f0189a3ddb4ebba6d94~mv2.png)

Post-processing uses a Dynamic Bayesian Network (DBN) with Viterbi decoding to align predictions with valid beat interval constraints. The model is evaluated across diverse public datasets spanning varied genres and tempos, matching state-of-the-art performance with a significantly smaller parameter count. Grad-CAM visualisations provide interpretability into which input regions drive predictions.

![Grad-CAM Visualization 1](./image_bt2.png)

![Grad-CAM Visualization 2](./image_bt3.png)

![Spectrogram and Activations](image_bt4.png)

*Fig. Spectrogram, ground truth annotation and generated activations*

Keywords: temporal event detection; temporal convolutional network (TCN); transformers; sequence modelling; signal processing
