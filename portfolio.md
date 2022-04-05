---
layout: page
title: portfolio
permalink: /portfolio/
---

<div class="blog">
<h5 class="section-intro">Projects</h5>
<h1 class="blog-heading">Thoughts, code and more.</h1>
<!--<h5 style="text-align: center;">Under construction, please come back again soon...</h5>-->
<hr>
<ul class="post-list">
    {% for project in site.portfolio reversed %}
    <li>
        <div class="row">
            <div class="column-img">
                <a class="post-title" href="{{ site.baseurl }}{{ project.url }}"><img class="thumbnail center" style="{{ project.style }}" src="{{ project.img }}"></a> 
            </div>
            <div class="column-project">
                <h2><a class="post-title" href="{{ site.baseurl }}{{ project.url }}">{{ project.title }}</a></h2>
                <p class="post-meta">{{ project.date | date: '%B %-d, %Y' }}</p>
                <p>{{ project.description }}</p>
            </div>
        </div>
        <hr />
    </li>
    {% endfor %}
  </ul>

<!--
{% for project in site.portfolio %}

{% if project.redirect %}
<div class="project">
    <div class="thumbnail">
        <a href="{{ project.redirect }}" target="_blank">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>
{% else %}

<div class="project ">
    <div class="thumbnail">
        <a href="{{ site.baseurl }}{{ project.url }}">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>

{% endif %}

{% endfor %}
-->
<div>

