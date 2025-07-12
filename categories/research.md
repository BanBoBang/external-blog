---
layout: default
title: "Research Articles"
---

{% for post in site.categories.research %}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) ({{ post.date | date: "%Y-%m-%d" }})
{% endfor %}
