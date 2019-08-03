---
layout: page
title: Browse the Collection
permalink: /collection/
---

<ul>
    {% for item in site.advocates %}
        <li><a href="{{ site.baseurl }}/advocates/{{ item.pid }}/">{{ item.label }}</a></li>
    {% endfor %}
</ul>