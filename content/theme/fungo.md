---
title: "Fungo"
keywords: ""
description: "fungo.dev official theme，support blog，document，page，customize page，and i18n"
thumb: "https://cdn.fundipper.cn/110119120/fundipper/official/project/lepu.webp"
image:
  - "/media/image/theme/fungo/customize.png"
  - "/media/image/theme/fungo/blog.png"
  - "/media/image/theme/fungo/document.png"
website: https://fungo.dev
repository: https://github.com/fundipper/theme
date: "2022-01-10"
star: 0
version: v1.0.0
license: mit
author: andy
category: "all"
tag:
  - "golang"
  - "tailwindcss"
  - "alpinejs"
---

## 介绍

---

fungo.dev official theme，support blog，document，page，customize page，and i18n

## 配置

---

```toml
[theme]
copyright = "copyright © 2021 - 2022 fungo.dev"
analysis = ""

[theme.color]
background = "bg-cyan-700"
font = "text-white"

[theme.image]
fungo = "/assets/img/logo/fungo.png"

[theme.link.header]
name = "nav"
data = [
    { name = "Doc", path = "/doc/overview/" },
    { name = "Theme", path = "/theme/" },
    { name = "Blog", path = "/post/" },
]

[theme.author.andy]
name = "andy.jiang"
avatar = "https://avatars.githubusercontent.com/u/9425368?s=400&u=a8083b0ebf6ac9f66be2f2c504044b72bbf807bd&v=4"
email = "150haomengting@163.com"
title = "Full Stack Developer"
summary = "10 years programming experience, familiar with golang, javascript, vue, tailwindcss. The latest is a static site engine named fungo."

[theme.tdk.index]
title = 'Fungo - simple and fast static site engine'
description = 'Fungo is a simple and fast static site engine, which can help you start your business without any programming.'
keywords = 'Fungo, static site engine'

[theme.tdk.themes]
title = 'theme store'
description = 'theme store of fungo, to find, download open source free themes, of course you can publish your own one.'

[theme.tdk.posts]
title = 'official blog'
description = 'official blog of fungo, for release new version, publish new tutorials'

[theme.tdk.archive]
title = 'archive'
description = ''

[theme.tdk.category]
title = 'category'
description = ''

[theme.tdk.tag]
title = 'tag'
description = ''
```

## 释义

---

1. theme

   主题设置

2. theme.color

   颜色配置

3. theme.image

   图片设置

4. theme.link

   链接设置

5. theme.author

   作者设置

6. theme.tdk

   TDK 设置
