---
layout: archive
title: "Papers"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<article class="archive__item" itemscope itemtype="http://schema.org/CreativeWork">
  <h2 class="archive__item-title">
    <a href="{{ post.url }}" itemprop="url">
      <span itemprop="name">{{ post.title }}</span>
    </a>
  </h2>
  <p class="archive__item-excerpt" itemprop="description">{{ post.excerpt }}</p>
  {% if post.co_authors %}
    <p class="archive__item-co-authors"><strong>Co-authors:</strong> {{ post.co_authors | markdownify }}</p>
  {% endif %}
</article>
