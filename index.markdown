---
title: Index
date: 2017-07-29 04:17:00 Z
permalink: "/"
---

Welcome to my wonderful site!

{% for post in site.posts %}
+ [{{ post.title }}]({{ site.url }}{{site.baseurl}}{{ post.url }})
{% endfor %}