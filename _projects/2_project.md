---
layout: page
title: How does translation boost degradation? 
description: modeling the flux of ribosomes on a mRNA and its effect on degradation
img: assets/img/rnadeg_intro.png
importance: 2
category: Molecular Biology
---
In the cell, messenger RNAs — or mRNAs — are translated into proteins and eventually degraded, but the relationship between translation and mRNA decay remains cloudy. 

In a recent collaboration with the [Chao Lab](https://www.fmi.ch/research-groups/groupleader.html?group=132#research) at FMI, we leverage stochastic models to discriminate between different mechanisms for the coupling of translation and mRNA degradation. The result suggests that degradation rate of mRNA increases each time a molecules is translated into protein.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/mrnaDegradation.png" title="Modeling the life of an mRNA molecule" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Modeling the life of an mRNA molecule with a degradation depending on ribosome flux.
</div>

This model predicts that the ribosome initiation frequency of an mRNA characterizes its degradation.

 <div class="row">
    <div class="col">
        {% include figure.html path="assets/img/mrnaDegradation_2.png" title="degradation curves" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The population of mRNA with the largest ribosome initiation frequency degrades the fastest.
</div>