---
layout: archive
permalink: /
title: "Hi, I'm Shehryar. I make things for the web."
---

<p>This is my personal website. Please excuse the mess as it's a work in progress.</p>

<h2><a href="{{ domain }}/portfolio/">Latest work</a></h2>

<div class="tiles">
{% for post in site.categories.portfolio limit:4 %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->