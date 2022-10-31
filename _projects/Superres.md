---
layout: page
title: Image Super Resolution using DCGAN
description: Estimating high resolution images when given low resolution images as input.
img: assets/img/Superres.png
importance: 1
category: Projects
---

<a href="https://paperswithcode.com/task/image-super-resolution">Single Image Super Resolution (SISR)</a> is a long standing problem in Computer Vision. Given an input low resolution (LR) image, the objective is to estimate a corresponding high resolution (HR) image. Since there is a one-to-many mapping from an LR to possible HR images, this remains a challenging problem in the community.

The current best approaches to the problem are deep learning based, pioneered by the SRCNN paper by Dong, et al. At the time of this project, the state-of-the-art benchmarks have been set mostly by GAN based methods such as the <a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Ledig_Photo-Realistic_Single_Image_CVPR_2017_paper.pdf">SRGAN by Ledig, et al.</a>

This project is my attempt at implementing a simple DCGAN to perform SISR at a scale of 4x.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Superres.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Some non cherry-picked outputs from my model. Not bad!
</div>


More details and code for this project are available <a href="https://github.com/md-hassan/Machine-Learning-Portfolio/tree/master/Image%20Super%20Resolution%20with%20DCGAN">here</a>.