---
layout: page
title: People
---

{% for person in site.data.people %}
  {{ person.name }}, {{ person.occupation }}<br>
{% endfor %}
