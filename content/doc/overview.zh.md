---
title: 概览
keywords: ""
description: ""
date: "2022-03-27"
lang: "zh"
slug: "overview"
---

         ____
        / __/  __  __   ____    ____ _  ____
       / /_   / / / /  / __ \  / __  / / __ \
      / __/  / /_/ /  / / / / / /_/ / / /_/ /
     /_/     \__,_/  /_/ /_/  \__, /  \____/
                            /____/ v0.2.9

[fungo](https://fungo.dev) is a simple and fast open-source static site generators base on golang.

## 亮点

---

1. Simple

   only 5 command, easy to use

2. Fast

   serve & build mode, both start less than 1s

3. I18N

   add multi-language not need to change any code

4. Customize

   can be blog & document & page and more

5. Markdown

   syntax highlighting & toc markdown support

6. SEO

   automatic seo friendly siteamp & rss

## 安装

---

local

    go install github.com/fundipper/fungo@latest

docker

    docker pull fundipper/fungo:latest

get more info, checkout [local](/doc/start/local/)， [docker](/doc/start/docker/) document

## 文档

---

the official website [fungo.dev](https://fungo.dev) is generate by `fungo` now.

- [document](/doc/overview/)

- [blog](/post/)

- [theme](/theme/)

## 特性

---

- [x] Support

  - [x] [Article](/doc/create/article/)

  - [x] [Page](/doc/create/page/)

  - [x] [Document](/doc/create/document/)

  - [x] [Customize](/doc/create/customize/)

  - [x] [I18N](/doc/create/i18n/)

- [x] [Markdown](/doc/config/site/markdown/)

  - [x] TOC

  - [x] META

  - [x] Emoji

  - [x] GFM (Table，Strikethrough，Linkify，TaskList)

  - [x] DefinitionList

  - [x] Footnote

  - [x] Typographer

  - [x] Mathjax

  - [x] Mermaid

  - [x] [Highlighting](/doc/config/site/highlighting/)

  - [x] [Image Lazyload](/doc/config/site/image/)

  - [x] [Link Reset](/doc/config/site/link/)

  - [x] [Video Embed](/doc/config/site/video/)

- [x] [Feeds](/doc/config/site/feeds/)

  - [x] RSS 2.0

  - [x] Atom 1.0

  - [x] JSON 1.1

- [x] SEO

  - [x] [Sitemap.xml](/doc/config/site/sitemap/)

  - [x] [Robots.txt](/doc/config/site/robots/)

## 感谢

---

- Language & Framework

  - [golang](https://go.dev/)

  - [tailwindcss](https://www.tailwindcss.com/)

  - [alpinejs](https://alpinejs.dev/)

- Tools & Libraries

  - [cobra](https://github.com/spf13/cobra)

  - [viper](https://github.com/spf13/viper)

  - [goldmark](https://github.com/yuin/goldmark)

  - [ristretto](https://github.com/dgraph-io/ristretto)

  - [httprouter](https://github.com/julienschmidt/httprouter)

  - [fsnotify](https://github.com/fsnotify/fsnotify)

  - [copy](https://github.com/otiai10/copy)

  - [go-git](https://github.com/go-git/go-git)

  - [etree](https://github.com/beevik/etree)
