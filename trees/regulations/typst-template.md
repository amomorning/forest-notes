---
author: Yichen Mo
date: 2025-10-28
title: Typst
---

``` typ
#import "_lib/kodama.typ": *

#meta("title", "Amo's blog")
#meta("author", "Yichen Mo")
#meta("date", "2025-10-28")
#meta("taxon", "Insight")

// 正文内容
#lorem(32)

// 通过相对路径嵌入 about.md 文件示例
#embed("./about.md", "Title (Locally)", numbering: true)

```
