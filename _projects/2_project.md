---
layout: page
title: Causal analysis
description: Interpretable fault diagnosis based on smartphone event tracking data
img: assets/img/CausalAnalyzer2.png
importance: 2
category: Work
---

Problem: The causes of smartphone quality problems are complex. Currently, data analysts mainly analyze the high-dimensional event tracking data manually to find the causes of failures, which is very time-consuming and laborious.

Approach: This project proposes a causal discovery algorithm based on multi-causal graph fusion and an efficient causal effect estimation approximation method to support the detection of reliable causal relationships. A visual analysis system is also developed to support users to interactively explore and analyze causal graphs, as well as to validate detection results.

Evaluation: Quantitative experiments on simulated data demonstrated the accuracy of our causal discovery algorithm at over 70%, and case studies demonstrate that the system helps analysts discover the cause of abnormal smartphone heating.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Causal-Workflow.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Workflow of the approach.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/CausalAnalyzer1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Stage 1: data configuration.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/CausalAnalyzer2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Stage 2: causal analysis.
</div>
