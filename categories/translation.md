---
layout: default
title: "Translation Articles"
---

{% for post in site.categories.translation %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%Y-%m-%d" }})
{% endfor %}
