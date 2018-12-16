---
layout: page
title: Images
---
<H1>Images on this Site</H1>
<br>

{% for file in site.static_files %}
  {% if file.image %}
    <img src="{{file.path}}" alt="{file.name}"
  {% endif %}
{% endfor %}  
