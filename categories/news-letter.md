---
layout: default
title: "Newsletter Articles"
---

{% for post in site.categories.news-letter %}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) ({{ post.date | date: "%Y-%m-%d" }})
{% endfor %}
