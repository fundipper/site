---
title: "指令"
keywords: ""
description: ""
date: "2021-01-01"
---

fungo仅有5个指令

### site

新建站点

    fungo site your-site-name

### file

新建文件

    fungo file you-source-name your-file-name

`source`目录已定义了[article](/doc/source/article/)，[document](/doc/source/document/)，[page](/doc/source/page/)三类资源类型

可对`已有资源`类型进行修改，亦可自定义其他[个性化资源](/doc/source/extend/)

### theme

新建主题

    fungo theme your-theme-name

若不自行开发模板，则无需使用

### serve

预览模式

    fungo serve

### build

编译模式

    fungo build
