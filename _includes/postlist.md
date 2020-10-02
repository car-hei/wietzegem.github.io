 <ul>
  {% for post in site.posts %}
   <li>
    {{ post.date | date: "%d.%m.%Y" }}<br><a href="..{{ post.url }}">{{ post.title }}</a>
   </li>
   <br>
  {% endfor %}
 </ul>
