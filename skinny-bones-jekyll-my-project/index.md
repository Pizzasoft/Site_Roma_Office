---
layout: home
permalink: /
image:
  feature: wood-texture-1600x800.jpg
---

### Nächste Aktivitäten und Events

<div class="tiles">
{% for post in site.categories.articles %}

  {% if post.tags contains 'video' %}
    {% include post-grid.html %}
  {% endif %}

{% endfor %}
</div><!-- /.tiles -->




### Vergangenes
