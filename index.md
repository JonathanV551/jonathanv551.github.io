---
layout: default
title: "Jonathan Vadala"
---

<section id="intro" class="main">
    <div class="spotlight">
        <div class="content">
            <header class="major">
                <h2>Welcome to My Portfolio</h2>
            </header>
            <p>Hi, I'm Jonathan Vadala. I'm passionate about software development, focusing on creating innovative solutions through SwiftUI, health technology, and creative coding projects.</p>
            <ul class="actions">
                <li><a href="/about-me" class="button">Learn More</a></li>
            </ul>
        </div>
    </div>
</section>

<section id="featured-projects" class="main special">
    <header class="major">
        <h2>Featured Projects</h2>
    </header>
    <ul class="features">
        <li>
            <h3>SwiftUI Canvas Integration</h3>
            <p>Exploring the integration of Canvas functionality with SwiftUI for enhanced user interfaces.</p>
        </li>
        <li>
            <h3>VizHealth</h3>
            <p>Innovative health visualization technology solutions.</p>
        </li>
        <li>
            <h3>Interactive Games</h3>
            <p>Creating engaging experiences like the number guessing game.</p>
        </li>
    </ul>
    <footer class="major">
        <ul class="actions special">
            <li><a href="/projects" class="button">View All Projects</a></li>
        </ul>
    </footer>
</section>

<section id="blog-preview" class="main special">
    <header class="major">
        <h2>Latest Updates</h2>
    </header>
    {% for post in site.posts limit:2 %}
    <article>
        <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
        <p>{{ post.excerpt }}</p>
    </article>
    {% endfor %}
    <footer class="major">
        <ul class="actions special">
            <li><a href="/blog" class="button">Read More</a></li>
        </ul>
    </footer>
</section>