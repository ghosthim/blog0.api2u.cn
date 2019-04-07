---
layout: page
title: About
description: 打码改变世界
keywords: Youngje Lee, 荣基
comments: true
menu: 关于
permalink: /about/
---
本站搭建于![](https://youngje.me/images/wiki/github-pages.png)之上，感谢 GitHub 提供无限量免费的 Page 空间

我是荣基。

喜欢自由，热爱自由。

展现出自己最真实的一面，做最好的自己。

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## 我的简介

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
