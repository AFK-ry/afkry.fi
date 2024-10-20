---
title: Frisbeer
permalink: /frisbeer/
---

Frisbeer on juomaurheilulaji, jossa heitetään frisbeetä ja juodaan kaljaa.

<h3 style="margin-bottom: 0;">Telegram</h3>
<ul style="margin-top: 8px;">
  <li><a href="https://t.me/joinchat/ENh2gUIL9W9L-fjR5lQa2w" target="_blank">Yleinen keskustelu</a></li>
  <li><a href="https://t.me/joinchat/ZJaLF_hEvq9hNjQ8" target="_blank">Pelit kanava</a></li>
</ul>

{% for post in site.categories.beer %}
  {% include post.html %}
{% endfor %}
