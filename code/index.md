---
layout: archive
title: "Good Code"
excerpt: "Thoughts on good, clean, wholesome code."
tags: []
image:
  feature:
  teaser:
---

<div class="tiles">
{% for post in site.categories.articles.musings %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->