---
layout: page
permalink: /publications/
title: publications
description:
sections: [article, talk]
---

{% for s in page.sections %}
  <h3 class="year">{{s}}s</h3>
  {% bibliography -f papers -q @{{s}}* %}
{% endfor %}
