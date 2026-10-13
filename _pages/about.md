---
permalink: /
title: "Haoqian Meng"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am an incoming Ph.D. student in Computer Science at Zhejiang University. I am currently an undergraduate student in the Elite Class at the School of Computer Science and Technology, Tianjin University (2023–2027), advised by Prof. Peng Zhang.

## Research Interests

My research interests include efficient large language model (LLM) inference, post-training quantization, low-precision numerical formats, and hardware-aware algorithms and kernels. I am particularly interested in making quantized LLM inference more accurate and efficient on modern accelerators.

## Publications

{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Education

- **2027–** — Incoming Ph.D. student in Computer Science, Zhejiang University.
- **2023–2027** — Undergraduate student, School of Computer Science and Technology, Tianjin University (Elite Class).
  - Advisor: Prof. Peng Zhang.
