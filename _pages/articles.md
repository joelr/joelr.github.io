---
layout: inner
title: Articles
permalink: /articles/
---

## A few articles..
--

{% for article in site.data.articles %}
  {% include small-post-content.html %}
{% endfor %}

