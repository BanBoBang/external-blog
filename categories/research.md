---
layout: default
title: "Research Articles"
category: research
permalink: /external-blog/categories/research/
---

{% for post in site.categories.research %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%Y-%m-%d" }})
{% endfor %}
