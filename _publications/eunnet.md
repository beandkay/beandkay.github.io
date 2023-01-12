---
title: "EUNNet: Efficient UN-normalized Convolution layer for stable training of Deep Residual Networks without Batch Normalization layer"
collection: publications
permalink: /publication/eunnet
excerpt: 'This paper is about the EUNNet, an Efficient UN-normalized Neural Networks.'
date: TBD
venue: 'IEEE Access'
paperurl: 'https://ieeexplore.ieee.org/document/9828384'
citation: '{Nguyen, Khanh-Binh and Choi, Jaehyuk and Yang, Joon-Sung (2023). &quot;EUNNet: Efficient UN-normalized Convolution layer for stable training of Deep Residual Networks without Batch Normalization layer.&quot; <i>IEEE Access</i>. 1(1).'
---
Batch Normalization (BN) is an essential component of the Deep Neural Networks (DNNs) architectures. It helps improve stability, convergence, and  generalization. However, studies are showing that BN might introduce several concerns. Although there are methods for training DNNs without BN using
proper weight initialization, they require several learnable scalars or accurate fine-tuning to the training hyperparameters. As a result, in this study, we aim to stabilize the training process of un-normalized networks without using proper weight initialization and to minimize the hyperparameters fine-tuning step. We propose EUNConv, an Efficient UN-normalized Convolutional layer, which helps train un-normalized Deep Residual Networks (ResNets) by using hyperparameters of the normalized networks. Furthermore, we introduce Efficient UN-normalized Neural Network (EUNNet), which replaces all of the conventional convolutional layers of ResNets with our proposed EUNConv. Experimental results show that the proposed EUNNet achieves the same or even better performance than previous methods in various tasks: image recognition, object detection, and segmentation. In particular, EUNNet requires less fine-tuning and less sensitivity to hyperparameters than previous methods.

[Download paper here](https://ieeexplore.ieee.org/document/9828384)

Recommended citation:
<pre>
TBU
</pre>