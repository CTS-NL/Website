---
layout: home
permalink: /
title:
image:
    feature: feature.jpg
---

<h3>Past Events</h3>

<div class="tiles">
{% for post in site.categories.media %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
