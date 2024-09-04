---
title: "過去の研究会"
---

<ul>
{% assign directory_pages = site.pages | where: "category", "past" %}
{% for page in directory_pages %}
<li><a href="{{ page.url }}">{{ page.title }}</a></li>
{% endfor %}
</ul>
