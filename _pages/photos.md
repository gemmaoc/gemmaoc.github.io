---
permalink: photos
layout: single
excerpt: "My Photos"
author_profile: true
classes: wide
---
<div>
{% for image in site.static_files %}
    {% if image.path contains 'assets/photos/Antarctica' %}
    <div>
        <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    </div>
    {% endif %}
{% endfor %}
</div>