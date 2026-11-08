---
layout: single
title: "黄登烽"
permalink: /
author_profile: true
description: "黄登烽，同济大学附属上海市第十人民医院病理科科研人员，研究方向包括结直肠癌、肿瘤微环境、单细胞转录组、空间组学与多组学。"
---

<section class="profile-hero">
  <p class="profile-hero__eyebrow">PATHOLOGY · CANCER BIOLOGY · MULTI-OMICS</p>
  <h2>从细胞图谱出发，理解肿瘤微环境</h2>
  <p class="profile-hero__lead">我在同济大学附属上海市第十人民医院病理科从事科研工作，聚焦结直肠癌生物学，并结合单细胞转录组、空间组学与多组学方法解析肿瘤微环境及疾病机制。</p>
  <div class="profile-hero__actions">
    <a class="profile-button profile-button--primary" href="/research/">了解研究方向</a>
    <a class="profile-button" href="/publications/">查看代表论文</a>
    <a class="profile-button" href="mailto:dfeng4127@ustc.edu">邮件联系</a>
  </div>
</section>

## 研究概览

<div class="research-grid">
  <article class="research-card">
    <span class="research-card__number">01</span>
    <h3>结直肠癌与肿瘤微环境</h3>
    <p>关注癌相关成纤维细胞、免疫细胞互作、细胞外基质重塑及免疫治疗响应。</p>
  </article>
  <article class="research-card">
    <span class="research-card__number">02</span>
    <h3>单细胞与空间组学</h3>
    <p>利用单细胞转录组和空间分辨数据刻画细胞异质性，发现潜在生物学机制。</p>
  </article>
  <article class="research-card">
    <span class="research-card__number">03</span>
    <h3>补体因子与巨噬细胞</h3>
    <p>研究巨噬细胞补体因子 D（CFD）缺失与结直肠癌发生发展的关系。</p>
  </article>
  <article class="research-card">
    <span class="research-card__number">04</span>
    <h3>神经生物学与昼夜节律</h3>
    <p>延续斑马鱼视觉功能、松果体神经元和细胞昼夜节律等方向的研究积累。</p>
  </article>
</div>

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
