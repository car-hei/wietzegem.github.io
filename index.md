---
title: Aktuelles
---
<post>
<ul>
  {% for post in site.posts %}
    <li>
	<h1><a href="{{ post.url }}" class="post">{{ post.title }}</a></h1>
	<br>
    (Eintrag vom {{ post.date | date: "%d.%m.%Y" }})
    {{ post.excerpt }}
	</li>
	<div style="text-align: right;"><a href="../{{ post.url }}">weiter >></a></div>
  {% endfor %}
</ul>
</post>

