---
layout: page
title: PDFs
---

# PDF Files

{% for file in site.static_files %}
   {% if file.pdf %}
<p><a href="{{site.baseurl}}/{{ post.url }}">{{file.name}}</a></p>
   {% endif %}
{% endfor %}   
