---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Economics, University of California, Berkeley (Ongoing)
* M.Sc. in Agricultural Economics, McGill University, 2020
* B.A. in Economics _(with Distinction)_, American University of Beirut, 2018
* Visiting Student, Michigan State University, 2017

Research
======

## Work in Progress
<ul>
{% for post in site.publications %}
  {% if post.status == "wip" %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}
</ul>

## Working Papers
<ul>
{% for post in site.publications %}
  {% if post.status == "working" %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}
</ul>

## Publications
<ul>
{% for post in site.publications %}
  {% if post.status == "published" %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}
</ul>
  
Presentations
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
