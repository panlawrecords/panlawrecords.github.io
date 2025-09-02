---
layout: default
title: Releases
---
<h1>Releases</h1>
<ul>
  {% for release in site.releases %}
    <li><a href="{{ release.url }}">{{ release.title }}</a> by {{ release.artist }}</li>
  {% endfor %}
</ul>
