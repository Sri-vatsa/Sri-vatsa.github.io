---
layout: post
title: You Only Spike Once (YOSO)
description: Improving Energy-Efficient Neuromorphic Inference to ANN-Level Accuracy (Paper)
img: /img/portfolio/YOSO-paper-title.png
style: "width:100%; height:auto;"
date: 2020-05-20 02:00:00 # GMT time
author: Srivatsa
---

<a class="text-link"
href="http://workshops.inf.ed.ac.uk/accml/papers/2020-isca/2nd_AccML_paper_1.pdf">Link
to full paper</a>

<h2>The Problem</h2>

Recently, artificial neural networks (ANNs) have emerged as the  most  promising
candidates  for  performing  a  wide  range  of tasks such as image
classification and recognition, object detection,speech recognition, and
speech-to-text translation. There have been significant improvements in the
classification accuracies of ANNs, and  in  2015,  ANNs  achieved  human-level
accuracy at  the ImageNet 2012 Visual Recognition Challenge. However,
the high classification performance of ANNs comes at the expense of a large number
of memory accesses and compute operations,which results in higher power and
energy consumption. 

Spiking neural networks (SNNs) have the potential to be a power-efficient
alternative to artificial neural networks (ANNs). SNNs are sparse, access very
few weights, and typically use addition operations instead of more
power-intensive multiply and accumulate (MAC) operations. 

The vast majority of neuromorphic hardware designs support rate-based SNNs,
where the information is encoded by spike rates. Generally, rate-based SNNs can
be inefficient as a large number of spikes will be transmitted and
processed during inference. A more efficient encoding scheme is the
time-to-first-spike (TTFS) encoding, where the information is encoded in
the relative time of arrival of spikes. In TTFS-based SNNs, each neuron can only
spike once during the entire inference process and this results in high sparsity.
While TTFS-based SNNs are more sparse than rate-based SNNs, they have yet to
achieve the same accuracy as rate-based SNNs. 

<h2>What we did</h2>

The main objective of our work was to accelerate the inference of TTFS-based SNNs on low-power devices, with minimal loss to accuracy.
Therefore, this work focused on (1) improving the classification performance of
TTFS-based SNNs, and (2) designing a low-power neuromorphic hardware accelerator
for performing inference of TTFS-based SNNs. The main contributions of this work
can be listed as follows:
<ul>
    <li>A new training algorithm that reduces the errors accumulated as a result of converting pre-trained neural network models to SNNs.</li> 
    <li> A novel low-power neuromorphic architecture, YOSO, designed to accelerate the inference operations of TTFS-based SNNs.</li> 
    <li>An end-to-end neuromorphic technique that demonstrates the state-of-the-art performance and accuracy for TTFS-based SNNs.</li> 
</ul>

<h2>Take Aways</h2>

<div class="img_row">
    <img class="col three" src="{{ site.baseurl }}/img/portfolio/yoso-accuracy-chart.png" alt="" title="accuracy results"/>
</div>
<div class="col three caption">
	A comparison to other neuromorphic accelerators based on accuracy on MNIST Dataset.
</div>

<div class="img_row">
    <img class="col three" src="{{ site.baseurl }}/img/portfolio/yoso-power-comp-chart.png" alt="" title="power performance"/>
</div>

<div class="col three caption">
	A comparison to other neuromorphic accelerators based on energy consumption per inference.
</div>
<br>
The YOSO accelerator is the only one that achieves both high accuracy and low-energy consumption at the same time.
TrueNorth-b consumes almost 3.83x more energy than YOSO to achieve its
higher accuracy, while TrueNorth-a gives up a significant amount of accuracy
(92.70% vs. 98.40% for our work) to achieve lower energy consumption.


More details can be found in our paper 
<a class="text-link"
href="http://workshops.inf.ed.ac.uk/accml/papers/2020-isca/2nd_AccML_paper_1.pdf">here.</a>

