---
layout: default
tags: other

---

<!-- Directory for the bloggish posts --> 


<ul id="blog_directory">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }},  {{post.date | date: "%B %Y" }} </a>
    </li>
  {% endfor %}
</ul>



