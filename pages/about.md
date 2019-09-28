---
layout: page
title: About
description: 打码改变世界
keywords: Youngje Lee, 荣基, api2u
comments: true
menu: 关于
permalink: /about/
---


我是 api2u 。

喜欢自由，热爱自由。

展现出自己最真实的一面，做最好的自己。

## 联系

* Email:me#api2u.cn(use @ replace #)

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


请我喝咖啡:[![Donate](https://blog.api2u.cn/images/wiki/donate.svg)](https://www.paypal.me/ghosthim)