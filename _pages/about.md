---
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am an incoming Ph.D. student in Computer Science at Zhejiang University, starting in Fall 2027 and advised by Prof. [Bohan Zhuang](https://bohanzhuang.github.io/). I am currently an undergraduate in the Elite Class at Tianjin University’s School of Computer Science and Technology.

## Research Interests

- Efficient LLM inference
- Low-precision and mixed-precision quantization
- GPU kernel and hardware-aware algorithm design

## Publications

{% include base_path %}
{% for post in site.publications reversed %}
  {% include publication-card.html %}
{% endfor %}

## Education

<div class="education-list">
  <div class="education-item">
    <a class="education-item__logo-link" href="https://www.zju.edu.cn/english/" aria-label="Zhejiang University">
      <img class="education-item__logo" src="{{ '/images/universities/zhejiang-university.png' | relative_url }}" alt="Zhejiang University seal" loading="lazy">
    </a>
    <div class="education-item__details">
      <div class="education-item__heading"><strong>Incoming Ph.D. Student in Computer Science</strong><span>2027–</span></div>
      <div><a href="https://www.zju.edu.cn/english/">Zhejiang University</a>, College of Computer Science and Technology</div>
      <div class="education-item__advisor">Advisor: Prof. <a href="https://bohanzhuang.github.io/">Bohan Zhuang</a></div>
    </div>
  </div>
  <div class="education-item">
    <a class="education-item__logo-link" href="https://en.tju.edu.cn/" aria-label="Tianjin University">
      <img class="education-item__logo" src="{{ '/images/universities/tianjin-university.png' | relative_url }}" alt="Tianjin University seal" loading="lazy">
    </a>
    <div class="education-item__details">
      <div class="education-item__heading"><strong>Undergraduate Student · Elite Class</strong><span>2023–2027</span></div>
      <div><a href="https://en.tju.edu.cn/">Tianjin University</a>, School of Computer Science and Technology</div>
      <div class="education-item__advisor">Advisor: Prof. Peng Zhang</div>
    </div>
  </div>
</div>
