---
layout: archive
title: "Files"
title-heading: true
permalink: /files/
author_profile: false
---

{% include base_path %}

<ul>
{% for file in site.static_files %}
      {% if file.path contains '/files/Stat423Pre' %}
          <li><a href="{{ file.path }}">{{ file.name }}</a></li>
      {% endif %}
{% endfor %}
</ul>