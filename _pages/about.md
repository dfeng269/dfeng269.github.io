---
layout: single
title: "个人主页"
permalink: /
author_profile: true
description: "黄登烽，同济大学附属上海市第十人民医院病理科科研人员，研究方向包括用单细胞以及空间多组学解析结直肠癌肿瘤微环境。"
---

<div class="update-slideshow" aria-label="论文代表图轮播">
  {% for item in site.data.updates limit:3 %}
    {% if item.image %}
    <a class="update-slideshow__slide update-slideshow__slide--{{ forloop.index }}" href="{{ item.url }}" target="_blank" rel="noopener noreferrer" aria-label="查看论文：{{ item.title }}">
      <img src="{{ item.image | relative_url }}" alt="{{ item.image_alt | default: item.title }}" {% if forloop.first %}loading="eager"{% else %}loading="lazy"{% endif %} decoding="async">
      <span>{{ item.image_caption | default: item.title }}</span>
    </a>
    {% endif %}
  {% endfor %}
</div>

## 最新动态

<div class="update-list">
{% for item in site.data.updates limit:5 %}
  <article class="update-item">
    <time datetime="{{ item.date }}">{{ item.date }}</time>
    <div class="update-item__body">
      <h3>{% if item.url %}<a href="{{ item.url }}" target="_blank" rel="noopener noreferrer">{{ item.title }}</a>{% else %}{{ item.title }}{% endif %}</h3>
      {% if item.description %}<p>{{ item.description }}</p>{% endif %}
    </div>
  </article>
{% endfor %}
</div>

## 学术经历

- **2020.09—至今**　同济大学附属上海市第十人民医院病理科，科研人员
- **2018.09—2020.08**　中国科学院脑科学与智能技术卓越创新中心，博士后
- **2012.09—2018.06**　中国科学技术大学，神经生物学博士
- **2008.09—2012.06**　蚌埠医科大学（原蚌埠医学院），生物科学学士

