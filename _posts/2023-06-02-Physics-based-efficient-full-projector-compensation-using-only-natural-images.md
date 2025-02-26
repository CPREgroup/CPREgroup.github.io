---
title: "Physics-based efficient full projector compensation using only natural images"
type: blog
selected: true
layout: post
author: Y. Li, W. Yin, J. Li, and X. Xie
post-image: "/assets/images/projector_compensation/structure.png"
description:  IEEE Transactions on Visualization and Computer Graphics
tags:
- Full Projector Compensation
- Projector Display
- Matrix Factorization
---

Achieving practical full projector compensation requires the projection display to adapt quickly to textured projection surfaces and unexpected movements without interrupting the display procedure. A possible solution to achieve this involves using a projector and an RGB camera and correcting both color and geometry by directly capturing and analyzing the projected natural image content, without the need for additional patterns. In this study, we approach full projector compensation as a numerical optimization problem and present a physics-based framework that can handle both geometric calibration and radiometric compensation for a Projector-camera system (Procams), using only a few sampling natural images. 
Our related code is available at <a href="https://github.com/kylin-leo/FullProjectorCompensation" target="_blank">GitHub</a>, 
and paper at <a href="https://www.techrxiv.org/articles/preprint/Efficient_Full_Projector_Compensation_using_Natural_Images/20359341" target="_blank">PDF</a>.

---

**The physical model of the Procams displaying images on textured surfaces:**<br>
![structure](/assets/images/projector_compensation/model_set.png)
<br><br>

**The temporary compensated images and simulated results of our compensation algorithm with the different number of iterations (iter=5, 10, 15, 20):**<br>
![structure](/assets/images/projector_compensation/result.png)

**The comparisons of the compensation results of our method and CompenNeSt++ on the projection surface:**<br>
![structure](/assets/images/projector_compensation/compare.png)

