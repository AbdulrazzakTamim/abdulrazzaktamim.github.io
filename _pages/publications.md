---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Publications

{% for post in site.publications reversed %}
  {% if post.status == "published" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Working Papers

{% for post in site.publications reversed %}
  {% if post.status == "working" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Work in Progress

{% for post in site.publications reversed %}
  {% if post.status == "wip" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
