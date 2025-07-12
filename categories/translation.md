---
layout: default
title: "Translation Articles"
---

{% for post in site.categories.translation %}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) ({{ post.date | date: "%Y-%m-%d" }})
{% endfor %}
