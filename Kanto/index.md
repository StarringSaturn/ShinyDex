---
title: Shiny Kanto (Art) Showcase
---


[Kanto](ShinyDex/Kanto) [Johto](ShinyDex/Johto) 
[Hoenn](https://starringsaturn.github.io/ShinyDex/Hoenn) [Sinnoh](https://starringsaturn.github.io/ShinyDex/Sinnoh) 
[Unova](https://starringsaturn.github.io/ShinyDex/Unova) [Kalos](https://starringsaturn.github.io/ShinyDex/Kalos) 
[Alola](https://starringsaturn.github.io/ShinyDex/Alola) [Galar](https://starringsaturn.github.io/ShinyDex/Galar) 
[Paldea](https://starringsaturn.github.io/ShinyDex/Paldea) [Miscellaneous](https://starringsaturn.github.io/ShinyDex/Misc)
<div>
{% for image in site.static_files %}
{% if image.path contains 'shinydex' %}
<img src="{{ site.baseurl }}{{ image.path }}" width = "150px" height = "300px" />
{% endif %}
{% endfor %}
</div>
