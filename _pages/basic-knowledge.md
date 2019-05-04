---
layout: archive
permalink: /basic-knowledge/
title: "Basic Knowledge"
author_profile: true
---

{% include base_path %}
<ul>
  {% for knowledge in site.basic-knowledge %}
      {% if knowledge.level == "scope" %}
           <li> 
		<a href="{{ knowledge.url }}"> {{ knowledge.title }}</a>
           </li>
      {% endif %}
      {% include archive-single.html %}
  {% endfor %}
</ul>
