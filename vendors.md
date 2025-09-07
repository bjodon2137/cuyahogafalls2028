---
layout: page
title: Vendors & Services
permalink: /vendors/
---

Below is a community-curated list. Submit a PR to add more.

## Tux / Dress Rentals
<ul>
{% for i in site.data.vendors.tux_rentals %}
  <li><a href="{{ i.url }}">{{ i.name }}</a> — {{ i.phone }}</li>
{% endfor %}
</ul>

## Senior Portrait Photographers
<ul>
{% for p in site.data.vendors.photographers %}
  <li><a href="{{ p.url }}">{{ p.name }}</a> — {{ p.phone }}</li>
{% endfor %}
</ul>
