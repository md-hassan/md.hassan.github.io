---
layout: page
title: 'LineEX: Data Extraction from Scientific Line Charts'
description: A system to extract data from line charts found in scientific papers. Not as easy as it sounds!
img: assets/img/LineEX.png
importance: 1
category: Research
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/LineEX.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The keypoint detection module of <code>LineEX</code>.
</div>

<!-- ADD CODE BUTTON LINK
https://stackoverflow.com/questions/15202799/jekyll-and-custom-css -->
<!-- <a href="https://github.com/Shiva-sankaran/LineEX" class="btn btn-sm z-depth-0" role="button">Code</a> -->
<!-- [`Code`](https://github.com/Shiva-sankaran/LineEX){: .btn}
<a href="https://wacv2023.thecvf.com/"> `Code` </a> -->


Scientific papers contain a large proportion of non-textual content, such as charts and images, that do not serve more purpose than visualization. This non-textual content, if successfully processed, can be used in designing high-quality scholarly search engines, machine-generated task-specific leaderboards, and scholarly assistants for impaired people. 

`LineEX` is a system to extract data from line charts found in scientific papers that leverages recent advancements in vision transformers. We propose a new loss function for line keypoint extraction that considers the local slope of lines, unlike previous methods that did not model this for keypoint extraction. We showcase better qualitative and quantitive results due to this novel loss function. We have also curated the most extensive synthetic line charts with more variations than previous datasets.

Our work has been accepted for publication at the <a href="https://wacv2023.thecvf.com/"> IEEE/CVF Winter Conference on Applications of Computer Vision (WACV) 2023</a>. The code is available <a href="https://github.com/Shiva-sankaran/LineEX">here</a>.
