---
layout: post
title: PMD Detection
description: Identifying speeding personal mobility devices from a traffic camera
img: /img/portfolio/govtech-logo.png
style: "width:100%; height:auto;"
date: 2019-04-01 12:00:00 # GMT time
author: Srivatsa
---

<h2>The problem</h2>

Personal mobility device (PMD) adoption has recently surged in major cities in
South East Asia. While many of the riders are responsible, some of them are
reckless in riding the PMDs, often speeding along pavements, leading to
avoidable deaths and injuries.

<h2>What we did</h2>

We worked on developing an end-to-end computer vision pipeline that attempts to
identify PMD riders who are travelling higher than the allowed speed. We trained
and used <b>FasterRCNN</b> and <b>YOLO</b> for identification of PMDs in a video
frame. Inference in actual deployment
was accelerated using <b>Nvidia's Jetson TX1</b> and <b>Intel's Movidius
Stick</b>. 

Watch a video demonstration of the system here:

<iframe src="https://drive.google.com/file/d/1aYN7Rqg40nJqvirLOygj1Uy3KyafcZx8/preview" width="640" height="400" frameBorder="0"></iframe>