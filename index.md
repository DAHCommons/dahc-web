---
title: DAHC - Digital Arts and Humanities Commons at UCSB
id: home
layout: default
---

**The Digital Arts & Humanities Commons (DAHC) is an open floor plan interdisciplinary co-working space for digital scholarship, pedagogy, and creative practice.** The Commons vision is a vibrant, accessible space for open research and interdisciplinary collaboration, bringing together faculty, graduate students, and undergraduates.

The DAHC is located on in Music 1410 (formerly the Arts Library) on the campus of UC Santa Barbara.

![Reception in DAHC]({{ site.baseurl }}/assets/images/gallery/01-Reception-in-DAHC.JPG)

## Recent News

<ul class="post-list">
  {% for post in site.posts limit:3 %}
    <li>
      {% assign date_format = site.minima.date_format | default: "%b %-d, %Y" %}
      <span class="post-meta">{{ post.date | date: date_format }}</span>
      <h3>
        <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
      </h3>
      <p>{{ post.excerpt }}</p>
      <hr>
    </li>
  {% endfor %}
</ul>

[...MORE NEWS]({{ site.baseurl }}/news)

## Apply to Join the DAHC

For full details on how to apply, see the [CFP]({{ site.baseurl }}/cfp).

The DAHC invites proposals from faculty-led research groups interested in meeting, conducting research, and teaching in the Commons, and in particular in making creative use of space. For example, these may take the form of makerspaces, hackerspaces, digital recording and editing kiosks or open labs. The space may be used for research projects, classes and class projects, or as a site for conferences and other events.