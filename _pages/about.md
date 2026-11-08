---
layout: single
title: "黄登烽"
permalink: /
author_profile: true
description: "黄登烽，同济大学附属上海市第十人民医院病理科科研人员，研究方向包括结直肠癌、肿瘤微环境、单细胞转录组、空间组学与多组学。"
---

## 最新动态

<div class="update-list">
{% for item in site.data.updates limit:5 %}
  <article class="update-item">
    <time datetime="{{ item.date }}">{{ item.date }}</time>
    <div>
      {% if item.url %}<a href="{{ item.url }}" target="_blank" rel="noopener noreferrer">{{ item.title }}</a>{% else %}<strong>{{ item.title }}</strong>{% endif %}
      {% if item.description %}<p>{{ item.description }}</p>{% endif %}
    </div>
  </article>
{% endfor %}
</div>

## 学术经历

- **2020.09—至今**　同济大学附属上海市第十人民医院病理科，科研人员
- **2018.09—2020.08**　中国科学院脑科学与智能技术卓越创新中心，博士后
- **2012.09—2018.06**　中国科学技术大学，神经生物学博士
- **2008.09—2012.06**　蚌埠医学院，生物科学学士

## 联系方式

欢迎围绕肿瘤微环境、单细胞与空间组学等方向开展学术交流与合作。  
邮箱：[dfeng4127@ustc.edu](mailto:dfeng4127@ustc.edu) · GitHub：[@dfeng269](https://github.com/dfeng269)
