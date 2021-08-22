---
layout: page
title: SHE
---

这是她的页面。

<ul>
{% for page in site.pages %}
  {% if page.dir == "/post/she/" %}
    <li> <a href="{{ page.url | relative_url }}">{{ page.title }}</a> </li>
  {% endif %}
{% endfor %}
</ul>
