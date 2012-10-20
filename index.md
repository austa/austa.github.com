---
layout: default
---

<ul class="ind" >
    {% for post in site.posts %}
    <br>
    <li><a href="{{ post.url }}">{{ post.title }}</a><br><span>{{ post.date | date: "%m.%d.%Y" }}</span></li>
    {% endfor %}
    <br>
</ul>
