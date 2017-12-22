---
layout: home
permalink: /
image:
  feature: colour.png
  teaser: colour.png
  thumb: colour.png
---

<h1>Latest posts</h1>
<div class="tiles">
{% for post in site.posts %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

