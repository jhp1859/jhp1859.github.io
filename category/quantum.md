---
layout: page
title: "Category: quantum"
permalink: /category/quantum/
---

## Posts in **quantum**

<ul>
{% for post in site.categories.quantum %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span style="font-size:0.9em; color:#666">— {{ post.date | date: "%Y-%m-%d" }}</span>
  </li>
{% endfor %}
</ul>
