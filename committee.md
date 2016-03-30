---
layout: page
title: Committee
permalink: /committee/
css: committee.css
---

{% for position in site.data.committee %}
  <span class="red big">{{ position.name }}:</span> {{ position.person }}
{% endfor %}
