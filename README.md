## Welcome to my blog

This blog is about my thoughts of tech, life and everything.

<ul>
  {% for post in site.posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
