---
title: Skinny
permalink: /skinny/
---

<ul>
{% for player in site.data.players %}
  <li>
{{ player.name}} {{player.position}}
  </li>
{% endfor %}
</ul>