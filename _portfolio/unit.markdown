---
layout: post
title: UNIT
description: Smart sensing system for made-to-measure tailors
img: /img/portfolio/unit-logo-2.png
style: "width:100%; height:auto;"
date: 2018-12-03 12:00:00 # GMT time
author: Srivatsa
---

<h2>The Problem</h2>

Traditionally, expert tailors take customer measurements, produce garments
in-house, and supervise the cutting of garments. In contrast, ‘modern tailors’
outsource the production of garments to expert tailors based overseas after
obtaining customer measurements. Currently, modern tailors use three methods to
obtain body measurements:
<l>
<li>Hire an expert tailor to take measurements of customers on a freelance basis</li>
<li>Get customers to measure themselves by following an online guide</li>
<li>Train their sales-staff to take measurements of customers</li>
</l>
<br>
The third option has become increasingly popular. After carefully studying the process of various tailors, we realised that <u>training sales staff to take measurements could be made more accurate and yield higher cost-savings</u>. We operationalised ‘accurate’ as ‘measuring within 5% of an expert tailor’s measurement’ and ‘cost-saving’ as ‘taking up less monetary resources and time compared to current methods’.

<h2>What we did</h2>

<em>Design statement:</em> <b>Build a guidance system for modern tailors to enable their salespersons to take
accurate body measurements at high cost-savings.</b>

We designed a solution that uses a guidance system to train salespersons in
modern tailor stores empowering them to replicate the mastery and
the finesse of their master tailor. With the use of a <u>smart tape, an interactive guidance system
and our proposed <b>pose estimation</b> algorithm</u>, we were not only able to obtain curved and linear
measurements of users with an accuracy of <b>+/- 5mm</b>
but also achieve time and cost savings.

The figure below shows a detailed breakdown of the different components within
the UNIT smart sensing platform:

<img class="center" src="{{ site.baseurl }}/img/portfolio/unit_architecture.png" alt=""
title="unit-architecture"/>
<div class="col three caption">
    Figure: Architecture diagram of the UNIT smart sensing system.
</div>

<h2>How it works</h2>

Our system is made up of two sub-systems: (1) a smart digital measuring tape that we
designed from scratch, and (2) a smart system with real-time feedback. The smart
system constantly tracks the smart tape to guide a salesperson step-by-step in obtaining accurate body
measurements from a customer.

Watch a full demonstration in the following video:

<iframe src="https://drive.google.com/file/d/14QH3OnhbTf6qJnuxz-orIDn4BeljxsKG/preview" width="100%" height="720" frameBorder="0"></iframe>

<div class="col three caption">
    Video: A demonstration of how the UNIT system works.
</div>

A detailed report of the project can be found <a class="text-link" href="https://drive.google.com/file/d/1yH_PVcHDeiybbYQR1RrGZaZMi58fEMLi/view?usp=sharing">here</a>.

The code can be found on GitHub <a class="text-link" href="https://github.com/Sri-vatsa/Unit">here</a>.