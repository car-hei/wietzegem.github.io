---
layout: default
---
<h1>{{ page.title }}</h1>
<br>
(Eintrag vom {{ page.date | date: "%d.%m.%Y" }})
{{ content }}
<div style="text-align: right;"><a href="javascript:history.back()" class="back"><< zurück</a></div>
