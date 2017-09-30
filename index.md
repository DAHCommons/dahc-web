---
title: DAHC - Digital Arts and Humanities Commons at UCSB
id: home
layout: default
---

**The Digital Arts & Humanities Commons (DAHC) is an open floor plan interdisciplinary co-working space for digital scholarship and pedagogy.** It hosts faculty-led research projects.

It is located on in Music 1410 (formerly the Arts Library) on the campus of UC Santa Barbarba.

[Apply to join the DAHC!]({{ site.baseurl }}/cfp)

## Recent News

<ul class="post-list">
  {% for post in site.posts limit 3 %}
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

[...MORE NEWS]({{ site.baseurl }}/news)
