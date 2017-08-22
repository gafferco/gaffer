---
layout: page
title: West Ham United
permalink: /west-ham-united/
---

<ul>
{% for player in site.data.players %}
  <li>
{{ player.name}} {{player.position}}
  </li>
{% endfor %}
</ul>