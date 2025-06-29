---
layout: archive
title: "个人简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

教育背景
======
* 硕士研究生 - 华中科技大学计算机科学与技术学院 (在读)
* 学士学位 - [本科学校] [专业] (年份)

工作经历
======
* 2024年至今: 研究生
  * 华中科技大学计算机科学与技术学院
  * 研究方向: [你的具体研究方向]
  * 导师: [导师姓名]

* [其他实习或工作经历]
  * [机构名称]
  * 工作内容: [具体工作描述]
  * 主管: [主管姓名]

技能专长
======
* 编程语言
  * Python, Java, C++, JavaScript
  * [其他编程语言]
* 技术栈
  * 机器学习框架 (TensorFlow, PyTorch等)
  * 数据库 (MySQL, MongoDB等)
  * [其他技术]
* 研究技能
  * 算法设计与分析
  * 数据挖掘与处理
  * [其他技能]

学术论文
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
学术报告
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
教学经历
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
获奖情况
======
* [获奖名称] - [颁发机构] (年份)
* [获奖名称] - [颁发机构] (年份)

项目经历
======
* [项目名称] - [项目描述] (年份)
* [项目名称] - [项目描述] (年份)
