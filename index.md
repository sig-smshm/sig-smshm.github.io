---
layout: home
title: "SIG-SMSHM: スマートマニュファクチャリングとシステム健全性管理研究会"
description: "SIG-SMSHMは人工知能学会第二種研究会のひとつで、スマートマニュファクチャリングとシステム健全性管理の研究開発について議論する場を提供することを目指します。"
---

# お知らせ
<ol style="list-style-type: none; max-height: 400px; overflow-y: auto;">
{% for post in site.posts limit:8 %}
  <li>{{ post.date | date: "%Y-%m-%d" }} &nbsp;»&nbsp; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ol>

* * *

# 第６回 スマートマニュファクチャリングとシステム健全性管理研究会

{% include 6th.md %}
