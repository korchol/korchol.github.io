---
title: Blog
permalink: /blog/
---

# Wszystkie wpisy

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d %b %Y" }}
{% endfor %}
