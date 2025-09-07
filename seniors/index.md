---
layout: page
title: Senior Directory
permalink: /seniors/
---

Below are example senior pages. Add more by copying one of the files in `_seniors/` and updating the front matter.

<ul>
  {% assign items = site.seniors | sort: "last_name" %}
  {% for s in items %}
    <li><a href="{{ s.url | relative_url }}">{{ s.first_name }} {{ s.last_name }}</a></li>
  {% endfor %}
</ul>
