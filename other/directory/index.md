---
layout: default
---

<!-- Directory for the bloggish posts --> 


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }} |  {{post.date | date: "%B %Y" }} </a>
    </li>
  {% endfor %}
</ul>







