---
layout: page
title: News
permalink: /news/
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span>— {{ post.date | date: "%b %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
