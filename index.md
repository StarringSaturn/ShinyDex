---
title: Shiny (Art) Showcase
---

{% for image in site.static_files %}
    {% if image.path contains 'shinydex' %}
        <img src="{{ site.baseurl }}{{ image.path }}" />
    {% endif %}
{% endfor %}
