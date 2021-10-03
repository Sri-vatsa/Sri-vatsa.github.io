---
layout: post
title: Pre-trained Encoders are All You Need 
description: Using pre-trained image representations and spatiotemporal attention for state representation learning in Atari (Paper)
img: /img/portfolio/pearl.png
style: "width:100%; height:auto;"
date: 2021-06-20 02:00:00 # GMT time
author: Srivatsa
---

<a class="text-link"
href="https://openreview.net/pdf?id=gIdZOAF0b4T">Link
to full paper (Accepted to International Conference on Machine Learning (ICML) Workshop 2021)</a>

<h2>The Problem</h2>

Data-efficiency and generalization are key challenges in deep learning and deep reinforcement
learning as many models are trained on large scale, domain-specific, and expensive-to-label
datasets. Self-supervised models trained on large scale uncurated datasets have shown successful
transfer to diverse settings.

<h2>What we did</h2>

1. We investigated the use of pretrained image representations and
   spatiotemporal attention for state representation learning in Atari. 

2. We also explored fine-tuning pretrained representations with self-supervised
   techniques, i.e., contrastive predictive coding, spatiotemporal contrastive
   learning, and augmentations.

<h2>Take Aways</h2>

Our results show that pretrained self-supervised models, not trained on domain-specific data, give competitive
performance compared to state-of-the-art self-supervised models, trained on large-scale
domain-specific data. Thus, pretrained models enable data-efficient and
generalizable state representation learning for RL.

<div class="img_row">
    <img class="col three" src="{{ site.baseurl }}/img/portfolio/attn.png" alt="" title="Attention visualization"/>
</div>
<div class="col three caption">
    A visualization of attention maps used by the pretrained encoders in related works and our work.
</div>

Moreover, our framework, PEARL (Pretrained Encoder and Attention for Representation Learning), investigates not only
using pretrained image representations but also pretrained spatio-temporal
attention. Our pretrained image representation model also uses attention and our
results show that attention helps state representation learning.

More details can be found in our paper 
<a class="text-link"
href="https://openreview.net/pdf?id=gIdZOAF0b4T">here.</a>

