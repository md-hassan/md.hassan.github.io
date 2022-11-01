---
layout: page
title: Colorizing Grayscale Images
description: Giving life (and color) to boring monochrome images.
img: assets/img/Colorize.png
importance: 2
category: Projects
---

Image colorization is a translation task that tries to estimate a plausible-looking colorized version of a given monochrome/grayscale image. Since there is a one-to-many mapping from grayscale to a possible colorized image, this is a highly undetermined problem.

I implemented the model as ResNet50 Autoencoder that translates an image from the <i>Lab</i> colorspace to the <i>RGB</i> colorspace in a supervised manner.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Colorize.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A couple of sample outputs from my model.
</div>


More details and code for this project are available <a href="https://github.com/md-hassan/Machine-Learning-Portfolio/tree/master/Image%20Super%20Resolution%20with%20DCGAN">here</a>.