---
title: "为什么要开发fungo"
keywords: ""
description: "fungo是一个使用GO语言开发的使用简单、运行快速的开源静态网站生成工具。"
lang: "zh"
slug: "why-we-made-fungo"
category: "News"
author: "andy"
thumb: "https://cdn.fundipper.cn/110119120/fundipper/official/project/ballet.webp"
date: "2021-10-11"
tag:
  - fungo
  - why
  - reason
---

当我们想

- 撰写一篇博客

- 编辑一些文档

- 展示一个产品

- 发布一个海报

- ……

我们希望有一款产品，可以具有以下特性：

1. 开源

2. 支持博客，文档，单页和自定义模型

3. 支持 Markdown 文档，支持 I18N

4. 支持拓展内容和定制主题

5. 支持预览和编译

6. 容易上手

7. SEO 友好

---

我们寻找并测试了一些广受好评的作品，包括但不限于

- Hugo

- Zola

- Hexo

- Gridea

- Zine

- ……

结果，无一例外的经历了`从入门到放弃`

---

**索性**

**我们来建造一个理想国吧！**

于是，便有了 Fungo

---

1. 开箱即用

   5 条指令`site，file，theme，serve，build`

2. 一站式服务

   做官网，做博客，做文档，做单页，做海报全都支持

3. 上手简单

   内容使用`markdown`呈现，支持 TOC，Meta，Mathjax，Mermaid，图片懒加载，视频嵌入，链接重置

   模板使用`go template`方案，几乎不含自创语法

   样式使用主流`tailwindcss`方案，无需重复学习
