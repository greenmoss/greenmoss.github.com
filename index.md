---
layout: page
title: "Kurt as GameDev"
tagline: Blogging progress on NotOrion
---
{% include JB/setup %}

## NotOrion is a 4X game based on Master of Orion 2

I am reimplementing the Master of Orion 2 game rules using python and pyglet. The project is currently called "NotOrion", though the name will change once I think of a better name. Once I am done with the reimplementation, I have a lot of ideas to extend gameplay rules and concepts.

## Meta/News

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
