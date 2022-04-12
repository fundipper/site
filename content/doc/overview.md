---
title: Why Fungo
keywords: ""
description: ""
date: "2022-03-27"
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

    3. 支持Markdown文档，支持I18N

    4. 支持拓展内容和定制主题

    5. 支持预览和编译

    6. 容易上手

    7. SEO友好

我们寻找并测试了一些广受好评的作品，包括但不限于

- Hugo

- Zola

- Hexo

- Gridea

- Zine

- ……

结果，无一例外的经历了`从入门到放弃`

**索性，我们来建造一个理想国吧！**

于是，便有了Fungo

1. 开箱即用

    仅含5条指令`site，file，theme，serve，build`

2. 一站式服务

    做官网，做博客，做文档，做单页，做海报全都支持

3.  上手简单

    模板使用`go template`方案，几乎不含自创语法
  
    样式使用主流`tailwindcss`方案，无需重复学习

**Thanks**

- [x] cmd https://github.com/spf13/cobra

- [x] config https://github.com/spf13/viper

- [x] router https://github.com/julienschmidt/httprouter

- [x] markdown https://github.com/yuin/goldmark

- [x] cache https://github.com/dgraph-io/ristretto

- [x] copy https://github.com/otiai10/copy

- [x] git https://github.com/go-git/go-git

- [x] watch file https://github.com/fsnotify/fsnotify

- [x] sitemap https://github.com/beevik/etree

- [x] render go/template

- [ ] feed