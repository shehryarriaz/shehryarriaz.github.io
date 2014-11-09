---
layout: archive
permalink: /
title: "I'm Shehryar. I make things out of code and pixels."
---

<p>Full-stack web developer passionate about code and design.</p>

<h2>Latest work</h2>

<div class="tiles">
{% for post in site.categories.portfolio limit:4 %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->