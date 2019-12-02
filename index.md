---
layout: default
---

{{ site.github.project_tagline }}

This is a demo index page.

Summer 2020: July 6 — August 16


## Rationale


## Summer School Format


## Organizing Committee

TODO


## Lecturers and Mentors

TODO


## Lecturers and Mentors

TODO


TODO: site maintained by

<ul>
{% for contributor in site.github.contributors %}
  <li>
    <img src="{{ contributor.avatar_url }}" width="32" height="32" />
    <a href="{{ contributor.html_url }}">{{ contributor.login }}</a>
  </li>
{% endfor %}
</ul>