---
layout: page
title: How do enhancers control promoter activity?
description: modeling enhancer-promoter communication
img: assets/img/figures-epmodel.png
importance: 1
category: Molecular Biology
---

Transcriptional control in mammals critically depends on enhancers, which control tissue specificity and
developmental timing of many genes. Enhancers are often located hundreds of kilobases away from target promoters and are thought to control gene expression by interacting with them in the three-dimensional space of the nucleus. However what type of interactions lead to, and how chromosome interactions are actually translated into, transcriptional outputs remains unclear. 

In a recent collaboration with the [Giorgetti Lab](https://giorgettilab.org/) at FMI, we proposed a mechanism in which stochastic enhancer-promoter interactions are transmitted into slower promoter ON/OFF dynamics through small numbers of intermediate regulatory processes.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/epcom_1.png" title="Modeling EP communication" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Model for enhancer-promoter communication and transcriptional response.
</div>

This model predicts that enhancer-promoter contact probabilities are translated non linearly into transcriptional levels, suggesting a potential mechanism for functional insulation of enhancers.

 <div class="row">
        {% include figure.html path="assets/img/epcom_2.png" title="transcriptional levels" class="img-fluid rounded z-depth-1" %}
</div>
<div class="caption">
    Model prediction of transcriptional levels function of enhancer-promoter contact probabilities. The sigmoidality of the curve implies a low sensitivity to changes in contact probabilities, at high contact probabilitis but a hyper sensitivity at low contact probabilities.
</div>