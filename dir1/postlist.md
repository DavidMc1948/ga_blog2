---
layout: page
title: Post List
---

<H1>Post List</H1>

{% for post in site.posts %}
  <li><a href="{{ post.url }}">{{post.title}}</a></li>
{% endfor %}
