---
title: Frisbeer
permalink: /frisbeer/
---

Frisbeer on juomaurheilulaji, jossa heitetään frisbeetä ja juodaan kaljaa.

{% for post in site.categories.beer %}
  {% include post.html %}
{% endfor %}