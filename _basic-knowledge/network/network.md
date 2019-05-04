---
collection: basic-knowledge
title: "计算机网络"
date:  2019-05-04 23:57:53
level: scope
scope: network
tags:
  - network
  - scope
  - basic-knowledge
categories:
  - basic-knowledge
  - scope
---
<ul>
    {% for knowledge in site.basic-knowledge %}
	{% if knowledge.scope == page.scope and knowledge.level == "knowledge" %}
	    <li>
		<a href="{{ knowledge.url }}">{{ knowledge.title }}</a>
	    </li>
	{% endif %}
    {% endfor%}
</ul>
