---
title: "Checkerboard Dropout: A Structured Dropout With Checkerboard Pattern for Convolutional Neural Networks"
collection: publications
permalink: /publication/checkerboard-dropout
excerpt: 'Dropout is adopted in many state-of-the-art Deep Neural Networks (DNNs) to ease the overfitting problem by randomly removing features from feature maps. However, previous studies show the limitations of dropout application to Convolutional Neural Networks (CNNs) due to an increase in spatial correlation of the zeroed-out values in the output feature maps, which limits the generalization and performance of the network. Recently, DropBlock has been successfully applied as an efficient structured dropout to mitigate the spatial correlation problem by dropping a continuous region and to allay the randomness of the conventional dropout. However, DropBlock does not completely remove the randomness. The reason is because DropBlock still randomly chooses the center points to generate regions to drops. This paper proposes a novel method, Checkerboard Dropout, to handle the randomness of the conventional dropout as well as DropBlock and to further reduce the spatial correlation between the zeroed-out values in output feature maps. The proposed method is evaluated with large-scale image classification and object detection tasks. Experimental results show that the proposed Checkerboard Dropout improves the top-1 accuracy by 2.17% for a baseline of ResNet-50 on ImageNet dataset, 1.44% AP for a baseline of RetinaNet with ResNet-50 + FPN backbone and outperformed the previous approach - DropBlock - 0.3% top-1 accuracy for ImageNet dataset and 0.64% AP for MS COCO dataset. Furthermore, the proposed Checkerboard Dropout also improves the model generalization, localization and segmentation capability toward complex objects through Grad-CAM and instance segmentation visualizations.'
date: 2022-07-13
venue: 'IEEE Access'
paperurl: 'https://ieeexplore.ieee.org/document/9828384'
citation: '{Nguyen, Khanh-Binh and Choi, Jaehyuk and Yang, Joon-Sung (2022). &quot;Checkerboard Dropout: A Structured Dropout With Checkerboard Pattern for Convolutional Neural Networks.&quot; <i>IEEE Access</i>. 10.'
---


[Download paper here](https://ieeexplore.ieee.org/document/9828384)

Recommended citation:
@article{nguyen2022checkerboard,
  title={Checkerboard Dropout: A Structured Dropout With Checkerboard Pattern for Convolutional Neural Networks},
  author={Nguyen, Khanh-Binh and Choi, Jaehyuk and Yang, Joon-Sung},
  journal={IEEE Access},
  volume={10},
  pages={76044--76054},
  year={2022},
  publisher={IEEE}
}