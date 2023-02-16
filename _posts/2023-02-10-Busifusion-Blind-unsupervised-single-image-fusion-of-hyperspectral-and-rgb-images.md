---
title: "BUSIFusion: Blind unsupervised single image fusion of hyperspectral and rgb images"
type: blog
selected: true
layout: post
author: J. Li, Y. Li, C. Wang, X. Ye, and W. Heidrich
post-image: "/assets/images/BUSIFusion.png"
description:  
tags:
- Unsupervised Image Fusion
- Blind Fusion
- Hyperspectral Image Fusion
---

Hyperspectral images (HSIs) provide rich spectral information that has been widely used in numerous computer vision tasks. However, their low spatial resolution often prevents their use in applications such as image segmentation and recognition. Fusing low-resolution HSIs with high-resolution RGB images to reconstruct high-resolution HSIs has attracted great research attention recently. In this paper, we propose an unsupervised blind fusion network that operates on a single HSI and RGB image pair and requires neither known degradation models nor any training data. Our method takes full advantage of an unrolling network and coordinate encoding to provide a state-of the-art HSI reconstruction. It can also estimate the degradation parameters relatively accurately through the neural representation and implicit regularization of the degradation model. The experimental results demonstrate the effectiveness of our method both in simulations and in our real experiments. The proposed method outperforms other state-of-the-art nonblind and blind fusion methods on two popular HSI datasets. Our related code and data is available at https://github.com/CPREgroup/Real-Spec-RGB-Fusion. <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10037221" target="_blank">PDF</a>
