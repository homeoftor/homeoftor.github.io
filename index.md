---
layout: default
title: News
nav_order: 1
---

Quote of the Day: _Bubble or Burn!_ -- KAZ

## Latest News

<ul class="posts">
   {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
   {% endfor %}
</ul>
