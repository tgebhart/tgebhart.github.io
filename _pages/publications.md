---
layout: page
permalink: /publications/
title: publications
description:
sections: [article, talk]
nav: true
---
<div class="publications">
{% for s in page.sections %}
  <h2 class="year">{{s}}s</h2>
  {% bibliography -f papers -q @{{s}}* %}
{% endfor %}
</div>
