---
collection: reading-notes
title: "Vim 实用技巧"
date: 2019-05-01 11:33:02
level: book
book: practical-vim
categories:
  - reading-notes
  - catalog
---

<ul>
    {% for note in site.reading-notes %}
  	{% if note.book == page.book and note.level == "chapter"%}
	    <li>
		<a href="{{ note.url }}">{{ note.title }}</a>
	    </li>
	{% endif %}
    {% endfor%}
</ul>
