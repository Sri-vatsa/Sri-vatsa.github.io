---
layout: post
title: The fight against Pneumonia using Machine Learning
description: Models to easily detect Pneumonia from chest x-rays
img: /img/portfolio/yolo-xray.png
style: "width:80%; height:auto;"
date: 2018-10-30 09:00:00 # GMT time
author: Srivatsa
---

<h2>The Problem</h2>
Pneumonia is the leading cause of death among children. However, it receives less than <b>2%</b> of the global development fund for health. It is also more prevalent in countries where there is insufficient medical expertise and lack of access to radiology diagnostics. Chest x-rays are the most common tool used to diagnose pneumonia. However, understanding chest X-rays require domain expertise and professional radiologists. We applied machine learning so that a computer can be used to detect signs of pneumonia given a chest x-ray, increasing the ease of access to resources for pneumonia detection. 

<h2>What we did</h2>

We successfully implemented and compared three machine learning models: <u>YOLOv3, RetinaNet and
Mask RCNN</u>. We tested and compared their effectiveness in recognising pneumonia
from chest x-rays. Our key finding was that an ensemble of RetinaNet models
supporting different input shapes outperformed other models, achieving the
highest <a class="text-link" href="https://en.wikipedia.org/wiki/Evaluation_measures_(information_retrieval)#Mean_average_precision">mean Average Precision (mAP)</a> of <strong>48.1%</strong>.

We presented this work at the 13th National University of Singapore (NUS)
School of Computing Term Project Showcase (STEPs).


<img class="center" src="{{ site.baseurl }}/img/portfolio/poster_final.png" alt=""
title="karina-aws"/>
<div class="col three caption">
    Figure: Our work summarized in a poster presented at the 13th NUS STEPs event.
</div>



