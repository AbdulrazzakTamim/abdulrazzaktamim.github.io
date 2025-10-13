---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  <p style="margin-bottom: 2em;">You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u></p>
{% endif %}

{% include base_path %}

<h2 style="color: #2c3e50; border-bottom: 3px solid #3498db; padding-bottom: 3px; margin-top: 3em; margin-bottom: 1.5em;">Publications</h2>

{% for post in site.publications reversed %}
  {% if post.status == "published" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2 style="color: #2c3e50; border-bottom: 3px solid #e67e22; padding-bottom: 3px; margin-top: 3em; margin-bottom: 1.5em;">Working Papers</h2>

{% for post in site.publications reversed %}
  {% if post.status == "working" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2 style="color: #2c3e50; border-bottom: 3px solid #95a5a6; padding-bottom: 3px; margin-top: 3em; margin-bottom: 1.5em;">Work in Progress</h2>

{% for post in site.publications reversed %}
  {% if post.status == "wip" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
