---
title: "being digital"
# sidebar: toc
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/thehelloworldproject{{ post.url }}">{{ post.title }}</a>
    </li>
    <p>
    {{post.content}}
    </p>
  {% endfor %}
</ul>