---
layout: page
permalink: /publications/
title: publications
description:
sections: [article]
nav: true
nav_order: 1
---
<div class="publications">
{% for s in page.sections %}
  <h2 class="year">{{s}}s</h2>
  {% bibliography -f papers -q @{{s}}* %}
{% endfor %}
</div>
