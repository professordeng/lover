---
layout: page
title: HE
---

这是他的页面。

<ul>
{% for page in site.pages %}
  {% if page.dir == "/he/" %}
    <li> <a href="{{ page.url | relative_url }}">{{ page.title }}</a> </li>
  {% endif %}
{% endfor %}
</ul>
