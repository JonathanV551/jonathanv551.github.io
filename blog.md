---
layout: default
title: Blog
permalink: /blog/
---

<section class="posts">
    <header class="major">
        <h1>Blog Posts</h1>
    </header>

    {% for post in site.posts %}
    <article>
        <header>
            <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
            <span class="date">{{ post.date | date: "%B %-d, %Y" }}</span>
        </header>
        {% if post.excerpt %}
        <p>{{ post.excerpt }}</p>
        {% endif %}
        <ul class="actions special">
            <li><a href="{{ post.url | relative_url }}" class="button">Read More</a></li>
        </ul>
    </article>
    {% endfor %}
</section>