---
title: Shiny (Art) Showcase
---

<div>
{% for image in paginator.posts %}
{% if image.path contains 'shinydex' %}
<img src="{{ site.baseurl }}{{ image.path }}" width = "150px" height = "300px" />
{% endif %}
{% endfor %}
</div>
