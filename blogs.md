---
title: blogs page
layout: blogs
---
<div>
    <h2>being digital</h2>
    <ul>
    {% for post in site.categories.beingdigital %}
        <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
        <!-- <p>
        {{post.content}}
        </p> -->
    {% endfor %}
    </ul>
</div>
<div >
    <h2>skeuomorph</h2>
    <ul>
    {% for post in site.categories.skeuomorph %}
        <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
        <p>
        <!-- {{post.content}} -->
        </p>
    {% endfor %}
    </ul>
</div>
<div >
    <h2>programming</h2>
    <ul>
    {% for post in site.categories.programming %}
        <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
        <p>
        <!-- {{post.content}} -->
        </p>
    {% endfor %}
    </ul>
</div>