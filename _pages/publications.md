---
layout: page
permalink: /publications/
title: Publications
description: All of my publications are available at Uliège institutional repository [ORBi]{https://orbi.uliege.be/profile?uid=p179634}.
years: [2023]
nav: true
nav_order: 1
---

## Journal articles
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

## International Conferences
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f conf -q @*[year={{y}}]* %}
{% endfor %}

</div>
