---
layout: default
title: Home
---

{% for post in site.posts %}
<div class="post">
  <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
  <div class="post-date">{{ post.date | date: "%G" | slice: -2, 2 }}w{{ post.date | date: "%V" }}.{{ post.date | date: "%u" }}</div>
  {{ post.excerpt }}
</div>
{% endfor %}