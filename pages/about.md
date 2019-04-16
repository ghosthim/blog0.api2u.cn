---
layout: page
title: About
description: 打码改变世界
keywords: Youngje Lee, 荣基
comments: true
menu: 关于
permalink: /about/
---


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

## 杂七杂八
> 本站部署于 `Netlify` 之上，感谢 Netlify 提供无限量免费的部署空间
[![Netlify Status](https://api.netlify.com/api/v1/badges/1a0ae327-3839-4330-9ad4-9be209f6f46d/deploy-status)](https://app.netlify.com/sites/tender-feynman-fdb755/deploys)

请我喝咖啡:[![Donate](https://youngje.me/images/wiki/donate.svg)](https://www.paypal.me/ghosthim)