---
layout: page
title: PDFs
---

# PDF Files

{% for file in site.static_files %}
   {% if page.url == '/assets/PDF/page.pdf' %}
[{{ page.title}}]({{ page.url }})
   {% endif %}
{% endfor %}   


{{ site.baseurl }}{% link /assets/PDF/A6 size new2.pdf %}



[A Five Minute Introduction]({{ site.baseurl }}{% link /assets/PDF/A6 size new2.pdf %})
