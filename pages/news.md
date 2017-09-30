---
layout: default
title: "News"
permalink: /news
nav: true
---

## Calendar

See the [DAHC Calendar]({{ site.baseurl }}/calendar)

## News

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      {% assign date_format = site.minima.date_format | default: "%b %-d, %Y" %}
      <span class="post-meta">{{ post.date | date: date_format }} {{ post.author }}</span>
      <h2>
        <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
      </h2>
	<p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
