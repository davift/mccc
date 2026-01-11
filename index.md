---
layout: default
---

# Welcome

This my gallery.

![Myna mini](mayna-mini.jpg)

## Features

{% for f in site.static_files %}
    {% if f.path contains '/mccc/' and f.extname == '.jpg' %}
![{{ f.name }}]({{ f.path | relative_url }})
    {% endif %}
{% endfor %}

