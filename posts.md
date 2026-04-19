---
layout: page
title: "Posts"
permalink: /posts/
---

[← About Me](/about/)

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) – {{ post.date | date: "%d.%m.%Y" }}
{% endfor %}
