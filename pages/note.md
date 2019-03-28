---
layout: page
title: Note
description: 人越学越觉得自己无知
keywords: 笔记, NOTE
comments: false
menu: NOTE
permalink: /note/
---

> 记多少命令和快捷键会让脑袋爆炸呢？

<ul class="listing">
{% for wiki in site.wiki %}
{% if wiki.title != "Wiki Template" %}
<li class="listing-item"><a href="{{ site.url }}{{ wiki.url }}">{{ wiki.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
