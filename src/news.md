---
title: News
layout: base
---

<div id="main">
<h2>News</h2><br>
<table cellspacing="0" cellpadding="0">
<tbody><tr><td id="main_archive" width="65%" valign="top">

{%- for item in collections.news %}
<div class="archive_item">
  <p><strong><a href="{{ item.url }}">{{ item.data.title }}</a></strong><br>
  <span class="archive_date">{{ item.data.pubdate}}</span></p>

  <p>{{ item.data.summary }}</p>
</div>
{%- endfor %}

</td><td id="league_archive" width="35%" valign="top">

<h5>Around the League</h5>

{% for item in leagueNews %}
<strong>{{ item.date }}</strong><br>{{ item.text }}<br>
<br>
{% endfor %}

</td></tr>
</tbody></table>

</div>