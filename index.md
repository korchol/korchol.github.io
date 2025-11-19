---
title: Witaj na moim blogu!
---

Cześć! Jestem [Twoje Imię], piszę o programowaniu, projektach i ciekawostkach technologicznych.

### Najnowsze wpisy
{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%d %b %Y" }}
{% endfor %}

[Przejdź do pełnego bloga](/blog/)
[O mnie](/about/)
