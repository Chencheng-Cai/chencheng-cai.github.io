---
layout: archive
title: "Files"
title-heading: true
permalink: /files/
author_profile: false
---

{% include base_path %}

<a href="/files/iGroup_Presentation.pdf">Colloquium Talk 2025<a><br>


<div>
{% for file in site.static_files %}
      {% if file.path contains '/files/Stat423Pre' and file.extname == '.ppt' %}
          <a href="{{ file.path }}"> {{file.path}} </a>
      {% endif %}
{% endfor %}
</div>