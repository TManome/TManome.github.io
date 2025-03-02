---
layout: post
title: "欢迎使用 Jekyll 构建博客！"
date: 2025-03-02 10:00:00
categories: 博客 技术
tags: Jekyll 教程 前端
image: /assets/images/jekyll-tutorial.jpg
---

## Jekyll 简介  

Jekyll 是一个静态网站生成器，特别适合用来搭建博客和文档网站。你只需使用 Markdown 撰写文章，Jekyll 会自动将它们转换为 HTML 页面。  

### 为什么选择 Jekyll？  

- 📝 **简单易用**：使用 Markdown 编写文章。  
- 🚀 **静态网站**：无需数据库，速度快，安全性高。  
- 🎨 **高度自定义**：支持 Liquid 模板引擎，轻松定制主题和插件。  

---

## 如何创建新文章？  

1. 在 `_posts` 目录下创建一个新的 Markdown 文件，命名格式为 `YYYY-MM-DD-文章标题.md`。  
2. 在文件开头添加前置数据 (Front Matter)：  

```yaml
---
layout: post
title: "我的第一篇 Jekyll 博客"
date: 2025-03-02 12:00:00
categories: 生活 随笔
tags: 日常
image: /assets/images/first-post.jpg
---
