---
layout: home
permalink: /
title:
image:
    feature: feature.jpg
---

This will be changed.

<div class="tiles">
{% for post in site.categories.media %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
