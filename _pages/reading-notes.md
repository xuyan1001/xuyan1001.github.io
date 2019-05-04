---
layout: archive
permalink: /reading-notes/
title: "Reading Notes"
author_profile: true
---

{% include base_path %}
<ul>
  {% for note in site.reading-notes %}
      {% if note.level == "book" %}
           <li> 
		<a href="{{ note.url }}"> {{ note.title }}</a>
           </li>
      {% endif %}
      {% include archive-single.html %}
  {% endfor %}
</ul>
