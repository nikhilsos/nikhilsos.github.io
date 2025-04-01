---
title: "Dual-Path Beat Tracking: Combining Temporal Convolutional Networks and Transformers in Parallel"
collection: publications
category: manuscripts
permalink: bt
excerpt: 'This study combined TCN and Roformer parallelu, to introduce inductive bias in the transformer model and improve the predictions while also reducing the parameters, the number of layers of transformer and associated parameters could be used as TCN is lightweight and provides decent results independently.'
date: 17 December 2024
venue: 'Applied Sciences, MDPI'
---

The Transformer, a deep learning architecture, has shown exceptional adaptability across fields, including music information retrieval (MIR). Transformers excel at capturing global, long-range dependencies in sequences, which is valuable for tracking rhythmic patterns over time. Temporal Convolutional Networks (TCNs), with their dilated convolutions, are effective at processing local, temporal patterns with reduced complexity. Combining these complementary characteristics, global sequence modeling from Transformers and local temporal detail from TCNs enhances beat tracking while reducing the model’s overall complexity.

![Beat Tracking Model Overview](/_publications/image.png)



To capture beat intervals of varying lengths and ensure optimal alignment of beat predictions, the model employs a Dynamic Bayesian Network (DBN), followed by Viterbi decoding for effective post-processing. This system is evaluated across diverse public datasets spanning various music genres and styles, achieving performance on par with current state-of-the-art methods yet with fewer trainable parameters. Additionally, we also explore the interpretability of the model using Grad-CAM to visualize the model’s learned features, offering insights into how the TCN-Transformer hybrid captures rhythmic patterns in the data.

![Grad-CAM Visualization 1](./image_bt2.png)



![Grad-CAM Visualization 2](./image_bt3.png)



![Spectrogram and Activations](image_bt4.png)



*Fig. Spectrogram, ground truth annotation and generated activations*

Keywords: beat tracking; temporal convolutional network (TCN); transformers; music information retrieval (MIR)
