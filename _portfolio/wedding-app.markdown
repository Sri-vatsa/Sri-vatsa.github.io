---
layout: post
title: Wedding Table Allocation
description: An SMT solver to allocate seats at a wedding
img: /img/portfolio/wedding-table.jpg
style: "width:100%; height:auto;"
date: 2018-06-18 05:00:00 # GMT time
author: Srivatsa
---

<h2>The Problem</h2>

If you have ever been to a wedding in Asia, you would have noticed that some of
the family members can be extremely picky on where they sit and who they sit
with. Accomodating peoples' preferences at a rather large wedding can be
extremely taxing on the couple that is getting married.

<h2>What we did</h2>

We framed the problem of seating people at a wedding table as a satisfiability
modulo theories (SMT) problem. We tried to identify rules that define how a
table should be seated:

<ul>
    <li>Couples should be seated together</li>
    <li>"Enemies" should not be seated together</li>
    <li>A person can only be seated at one table</li>
    <li>There are different restrictions on how many people can be seated at different tables</li>
    <li>Tables are sometimes restricted by guests' dietary preferences</li>
</ul>

To find a table arrangement that fulfills as many constraints listed by a couple
as possible, we used the <a class="text-link"
href="https://github.com/Z3Prover/z3">Z3 theorem prover</a> and <a
class="text-link" href="https://github.com/pysmt/pysmt">PySMT</a> libraries to
develop a solution.

Our solution is on <a class="text-link" href="https://github.com/Sri-vatsa/weddingapp">github</a>.
