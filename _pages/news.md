---
layout: page
title: news
permalink: /news/
description: Updates, in reverse chronological order.
nav: false
---

{% comment %} Edit news in _data/news.yml. This page shows every item. {% endcomment %}
<div class="mt-8">
  {% include news_items.liquid show_day=true %}
</div>
