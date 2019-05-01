---
layout: archive
permalink: /reading-notes/
title: "Reading Notes"
author_profile: true
---

{% include base_path %}
<ul>
  {% for note in site.reading-notes %}
      <li> 
	<a href="{{ note.url }}"> {{ note.title }}</a>
      </li>
    {% include archive-single.html %}
  {% endfor %}
</ul>
