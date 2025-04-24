
---
layout: default
title: Writing
---
Essays & notes on SEO, data, and purposeful living.

<ul>
{% for post in site.posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a> <small>– {{ post.date | date: "%d %b %Y" }}</small></li>
{% endfor %}
</ul>
