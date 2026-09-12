---
layout: page
permalink: /publications/
title: publications
description: Publications in reversed chronological order.
nav: true
nav_order: 2
---

{% comment %}
  Peer-reviewed papers come from _bibliography/papers.bib, grouped by year.
  Talks, posters and other non-paper items come from
  _bibliography/presentations.bib and are listed below under one heading.
  Card markup is in _layouts/bib.liquid; the scholar settings are in _config.yml.
{% endcomment %}
<div class="mt-10">
  {% bibliography %}

  <h3 class="bib-list">Others&thinsp;/&thinsp;Presentations</h3>
  {% bibliography -f presentations --group_by none %}
</div>
