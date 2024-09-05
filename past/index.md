---
title: "過去の研究会"
---

## 予稿集（人工知能学会第二種研究会資料）

- 第１回 [https://www.jstage.jst.go.jp/browse/jsaisigtwo/2024/SMSHM-001/_contents/-char/ja](https://www.jstage.jst.go.jp/browse/jsaisigtwo/2024/SMSHM-001/_contents/-char/ja)

## 過去の研究会CFP

<ul>
{% assign directory_pages = site.pages | where: "category", "past" %}
{% for page in directory_pages %}
<li><a href="{{ page.url }}">{{ page.title }}</a></li>
{% endfor %}
</ul>
