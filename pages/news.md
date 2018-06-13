---
title: News
permalink: "/news"
layout: default
nav: true
---

## Photo Gallery

Check out [photos from our recent events]({{ site.baseurl }}/gallery).

## Bulletin Board

Let the DAHC community know about upcoming events, ongoing projects, and recent awards by sharing flyers and pictures through the [virtual bulletin board](https://goo.gl/forms/37ssmQ9iK4sNJM5O2).

## News & Events

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      {% assign date_format = site.minima.date_format | default: "%b %-d, %Y" %}
      <span class="post-meta">{{ post.date | date: date_format }}</span>
      <h2>
        <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
      </h2>
      <p>{{ post.excerpt }}</p>
      <hr>
    </li>
  {% endfor %}
</ul>
