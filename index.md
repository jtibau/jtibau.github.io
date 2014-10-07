---
layout: page
title: jatb - Ramblings
---
{% include JB/setup %}

{% for post in site.posts %}
  <h3>{{ post.title }}</h3>
  {{ post.content }}
{% endfor %}
