---
layout: default
title: gallery
permalink: /gallery/
nav: true # hidden from the menu until ready; set to true to show it
nav_order: 4
---

<div class="post research-page">
  <header class="post-header">
    <h1 class="post-title">Gallery</h1>
    <div class="accent-rule"></div>
  </header>

  <nav class="gallery-jump">
    {% for section in site.data.gallery %}
      {% if section.items and section.items.size > 0 %}
        {% assign sid = section.id | default: section.title | slugify %}
        <a class="link-box" href="#{{ sid }}">{{ section.title }}</a>
      {% endif %}
    {% endfor %}
  </nav>

{% for section in site.data.gallery %}
{% if section.items and section.items.size > 0 %}
{% assign sid = section.id | default: section.title | slugify %}
<section class="gallery-section" id="{{ sid }}">
<h2 class="section-label"><a href="#{{ sid }}">{{ section.title }}</a></h2>
{% if section.description %}<p class="gallery-desc">{{ section.description }}</p>{% endif %}
<div class="gallery-grid{% if section.thumb %} thumb-{{ section.thumb }}{% endif %}">
{% for item in section.items %}
<div class="gallery-item">
{% include figure.liquid path=item.image alt=item.caption class="img-fluid" zoomable=true %}
{% if item.caption %}<p class="small-caption">{{ item.caption }}</p>{% endif %}
</div>
{% endfor %}
</div>
</section>
{% endif %}
{% endfor %}

</div>
