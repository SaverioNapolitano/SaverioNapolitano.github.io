---
layout: default
title: Blog
permalink: /blog/
---

<section class="section">
  <div class="wrapper">
    <div class="section-head reveal">
      <p class="kicker">Writing</p>
      <h2>Notes &amp; experiments.</h2>
    </div>

    {% if site.posts.size > 0 %}
    <ul class="post-list">
      {% for post in site.posts %}
      <li class="post-item reveal">
        <a href="{{ post.url | relative_url }}">
          <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: '%b %-d, %Y' }}</time>
          <h3>{{ post.title }}</h3>
          {% if post.excerpt %}<p>{{ post.excerpt | strip_html | truncate: 140 }}</p>{% endif %}
        </a>
      </li>
      {% endfor %}
    </ul>
    {% else %}
    <p class="empty">No posts yet — check back soon.</p>
    {% endif %}
  </div>
</section>
