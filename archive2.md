---
layout: page
title: Archive 2
---

  <ul>
    {% for post in site.posts %}
      <li><small></small><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></small></li>
    {% endfor %}
  </ul>
