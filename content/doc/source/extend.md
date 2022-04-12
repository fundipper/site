---
title: "拓展资源"
keywords: ""
description: ""
date: "2021-01-01"
---

当已定义资源无法满足需求时

用户可基于`yaml`语法，拓展自定义资源

例子:

在`source`目录，新建`theme.yaml`资源

    title: ""
    keywords: ""
    description: ""
    date: ""
    lang: ""
    slug: ""
    category: ""
    tag: ["", "", ""]
    thumb: ["", "", ""]
    nav: ["", "", ""]

然后使用`fungo file theme your-theme-name`

即可生成自定义的`theme`类型的资源

使用 cat 命令查看文件

```

➜ cat your-theme-name.md
---
title: your-product-name
description: ""
keywords: ""
date: "2022-03-31"
lang: ""
category: ""
slug: ""
tag:
  - ""
  - ""
  - ""
thumb:
  - ""
  - ""
  - ""
nav:
  - ""
  - ""
  - ""
---
```

> 因 map 随机遍历，故无法保证`meta`的顺序
> 是否调整顺序都不影响文件解析
