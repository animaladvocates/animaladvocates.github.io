---
layout: page
title: Browse the Collection
permalink: /collection/
---

<p>Choose the name of an animal advocate below to access the interview.</p>

<ul>
    {% for item in site.advocates %}
        <li class="browse-items"><a href="{{ site.baseurl }}/advocates/{{ item.pid }}/">{{ item.label }}</a><br><span class="browse-byline">Interviewed by {{item.interviewer}}.</span></li>
    {% endfor %}
</ul>