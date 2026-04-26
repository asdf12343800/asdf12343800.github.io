---
layout: home  # 使用 minima 主题自带的首页布局
title: 首页
---

# 欢迎来到我的博客！

这是我的个人博客，分享技术笔记和生活随笔。

## 最新文章
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
