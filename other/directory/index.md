---
layout: default
tags: other

---

<!-- Directory for the bloggish posts --> 

<div id="blog_directory">
  <ul >
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}">{{ post.title }},  {{post.date | date: "%B %Y" }} </a>
      </li>
    {% endfor %}
  </ul>
</div>
