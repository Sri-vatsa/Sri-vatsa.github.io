---
layout: post
title: Differential Privacy in Healthcare
description: Comparative study of privacy-preserving techniques for deep learning (Paper)
img: /img/portfolio/DP_diagram.png
style: "width:100%; height:auto;"
date: 2019-12-01 13:00:00 # GMT time
author: Srivatsa
---

<a class="text-link"
href="https://www.dropbox.com/s/hwub4w4cfx7gc6l/A%20Comparative%20Study%20of%20Privacy-Preserving%20Techniques%20For%20Deep%20Learning.pdf?dl=0">Link
to full paper</a>

<h2>The Problem</h2>

In recent years, along with the rise of machine learning across a wide plethora of applications, we see massive troves of data being collected from individuals. Be it users' online activity or diagnosis reports, large amounts of sensitive data are collected by a growing number of institutions, ranging from hospitals and government bodies to private companies and research organizations. This has ushered growing concerns associated with a potential loss of user privacy.

<h2>What we did</h2>

With growing concerns over privacy, this work aims to study privacy preservation
techniques using the differential privacy framework and, draw comparisons
between medical and non-medical datasets from a privacy standpoint. We compare
the use of Differentially Private Stochastic Gradient Descent (DP-SGD) and
Private Aggregation of Teacher Ensembles (PATE) on three publicly available
datasets.

<img class="center" src="{{ site.baseurl }}/img/portfolio/DP_diagram.png" alt=""
title="differential-privacy diagram"/>
<div class="col three caption">
	Figure 1: Comparison between Global and Local Differential Privacy
</div>

<h2>Take Aways</h2>

In the past decade, Differential Privacy has become the de-facto framework for performing privacy analysis. There
are numerous relaxations of Differential Privacy with the most prominent ones
being epsilon,delta-Differential Privacy (DP) and R\'enyi Differential
Privacy (RDP).

<ul>
    <li>Healthcare datasets are usually plagued with missing values and class imbalance problems. It was found that these factors affected the utility privacy trade-off significantly.</li>
    <li> The most important factors were found to be the complexity of the dataset and the type of noise applied.</li>
</ul>

More details can be found in the paper 
<a class="text-link"
href="https://www.dropbox.com/s/hwub4w4cfx7gc6l/A%20Comparative%20Study%20of%20Privacy-Preserving%20Techniques%20For%20Deep%20Learning.pdf?dl=0">here.</a>

