---
title: West Ham United
---

<ul>
{% for west_ham_player in site.data.west_ham_players %}
  <li>
{{ west_ham_player.name}} {{ west_ham_player.position }}
  </li>
{% endfor %}
</ul>

<ul>
{% for liverpool_player in site.data.liverpool_players %}
  <li>
{{ liverpool_player.name}} {{ liverpool_player.position }}
  </li>
{% endfor %}
</ul>