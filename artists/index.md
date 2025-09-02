---
layout: default
title: Artists
---
<h1>Artists</h1>
<ul>
  {% for artist in site.artists %}
    <li><a href="{{ artist.url }}">{{ artist.name }}</a></li>
  {% endfor %}
</ul>
