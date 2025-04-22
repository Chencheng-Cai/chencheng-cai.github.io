---
layout: archive
title: "Files"
title-heading: true
permalink: /files/
author_profile: false
---

{% include base_path %}

<ul>
{% for file in site.files %}
      {% if file.path contains '/files/Stat423Pre' and file.extname == '.ppt' %}
          <li><a href="{{ file.path }}">{{ file.path }}</a></li>
      {% endif %}
{% endfor %}
</ul>