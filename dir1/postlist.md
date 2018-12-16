---
layout: page
title: Post List
---

<H1>Post List</H1>

{% for post in site.posts %}
   <li><a href="{{site.baseurl}}/{{ post.url }}">{{post.title}}</a></li>
{% endfor %}
