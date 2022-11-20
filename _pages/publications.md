---
layout: page
permalink: /publications/
title: Publications
years: [2023, 2022]
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

<br>
<h2> Poster Presentations </h2>
---
<p style="text-align:left;">
    <b>3D Model Retrieval Using Multi-modal Inputs </b>
    <span style="float:right;font-size:26.0pt;color:var(--global-divider-color)">
        2022
    </span>
  <br>
  <u>Muhammad Yusuf</u> <u>Hassan*</u>, Shivasankaran V P*
  <br>
  <i>Undergraduate Research Showcase, IIT Gandhinagar </i>
</p>

<p style="text-align:left;">
    <b>Information Extraction from Scientific Charts </b>
    <span style="float:right;font-size:26.0pt;color:var(--global-divider-color)">
        2021
    </span>
  <br>
  <u>Muhammad Yusuf</u> <u>Hassan</u>
  <br>
  <i>Summer Research Internship Program, IIT Gandhinagar </i>
</p>
