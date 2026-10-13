---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

## Education

- **2027–** — Incoming Ph.D. student in Computer Science, Zhejiang University.
- **2023–2027** — Undergraduate student, School of Computer Science and Technology, Tianjin University (Elite Class).
  - Advisor: Prof. Peng Zhang.

## Publications

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>
