---
layout: archive
permalink: /
title: "Latest Posts"
---

This will be changed.

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
