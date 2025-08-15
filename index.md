---
layout: default
title: Home
---

{% for post in site.posts %}
<div class="post">
  <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
  <div class="post-date">{{ post.date | date: "%Gw%V.%u" }}</div>
  {{ post.excerpt }}
</div>
{% endfor %}