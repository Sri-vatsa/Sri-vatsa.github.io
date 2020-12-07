---
layout: post
title: Karina
description: Guidance system for In-Vitro Fertilization (IVF) patients
img: /img/12.jpg
date: 2018-11-15 08:00:00 # GMT time
author: Srivatsa
---

<h2>The Problem</h2>
<ul>
<li>Complexity of IVF treatment often leads to patients missing critical steps</li>
<li>IVF Patients may face anxiety about fertility issues</li>
<li>Hospitals are unable to provide dedicated enquiry channels to patients</li>
</ul>

<h2>What we did</h2>

My team and I built the Karina platform which has both a patient application and
a physician dashboard.

<div class="img_row">
    <img class="col one" src="{{ site.baseurl }}/img/portfolio/patient-chatbot.jpg" alt="" title="patient-chatbot"/>
    <img class="col two" src="{{ site.baseurl }}/img/portfolio/physician-dashboard.png" alt="" title="physician-dashboard"/>
</div>
<div class="col three caption">
    Left: Screenshot of a user using the in-app chatbot. Right: Physician dashboard showing page to retrieve patient data.
</div>

The technical architecture of Karina was built based on three fundamental
principles (1): Security, (2): Elasticity & Scalability, and (3): Availability.
Using these design principles, we deployed a fully cloud-native application.

<img class="center" src="{{ site.baseurl }}/img/portfolio/karina-cloud-infrastructure.png" alt=""
title="karina-aws"/>
<div class="col three caption">
    Figure: The full architecture of the cloud-native application on Amazon Web Services(AWS) cloud.
</div>

Through Karina, we were able to:
<ul>
<li>Provide guidance at each step of the IVF process</li>
<li>Provide emotional and psychological support to IVF patients</li>
<li>Make pertinent information about IVF readily accessible to patients</li>
<li>Build a safe community for IVF patients to connect and share</li>
</ul>

