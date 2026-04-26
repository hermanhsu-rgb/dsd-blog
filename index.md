---
layout: home
title: DSD数字化微笑设计
---

# DSD数字化微笑设计

欢迎来到 **DSD国际中文版** 博客！

这里汇集关于数字化微笑设计（Digital Smile Design）的专业资讯、案例分析和技术探讨。

## 最新文章

{% for post in site.posts limit:5 %}
### [{{ post.title }}]({{ post.url | relative_url }})
*{{ post.date | date: "%Y-%m-%d" }}*

{{ post.excerpt | strip_html | truncate: 150 }}

{% endfor %}

## 关于DSD

数字化微笑设计（DSD）是一种以患者面部美学为导向的牙科治疗规划方法。通过数字化工具，在治疗前可视化最终效果，让患者参与设计过程，实现真正的个性化美学修复。

## 关于作者

**Herman Hsu（许恒恺）**
- DSD Master（2016年认证）
- DSD Instructor（2019年认证）
- D4 Dental创始人
- 已培养DSD认证医师300余名

---

*本站所有文章均为原创内容，转载请注明出处。*
