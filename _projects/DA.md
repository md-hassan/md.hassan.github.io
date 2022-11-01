---
layout: page
title: Domain Adaptation for MRI Segmentation
description: A new benchmark for Domain Adaptation for the task of Brain MRI segmentation.
img: assets/img/DA.jpg
importance: 2
category: Research Projects
---

Accurate brain segmentation is critical for Magnetic Resonance Imaging (MRI) analysis pipelines. However, the segmentations produced by Machine Learning models often degrade in the presence of domain shifts between the test and train sets data distributions. These domain shifts are expected due to factors such as scanner hardware and software differences, technology updates, and MRI acquisition parameters. Domain Adaptation (DA) methods can make Machine Learning models more resilient to these domain shifts. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/DA_prob.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The problem of Domain Shift: we observe a loss in performance when moving from training to testing data distributions.
</div>

Our work proposes a new benchmark (<a href="https://www.ccdataset.com/brain-mri-segmentation-playground">available here</a>) for investigating DA techniques for brain MR image segmentation using data collected across sites with scanners from different vendors (Philips, Siemens, and General Electric). We provide labeled data, publicly available source code for a set of baseline and DA models, and a benchmark for assessing different brain MR image segmentation techniques. 

This work has been published in the journal <i>Frontiers in Neuroinformatics</i>, <a href="https://www.frontiersin.org/articles/10.3389/fninf.2022.919779/full">available here</a>. The code can be found <a href="https://github.com/ParisaSaat/Brain-MR-Segmentation-Playground">here</a>.