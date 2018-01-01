---
layout: home
permalink: /
image:
  feature: pattern3.jpg
  teaser: pattern3.jpg
  thumb: pattern3.jpg
---

<h1>Latest posts</h1>
<div class="tiles">
{% for post in site.posts %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

