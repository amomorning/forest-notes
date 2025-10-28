---
author: Yichen Mo
date: 2025-10-28
title: Writing Tools
---

[Kodama](https://github.com/kokic/kodama/tree/main) 支持同时使用 markdown 和 Typst 写作.

### Usage


```sh

# 从 github 安装
cargo install --git https://github.com/kokic/kodama.git

# 检查版本
kodama -V

# 创建新站点（需要独立重新建立文件夹）
kodama new site new_path

# 用户在新建的/trees目录下使用 Markdown 或 Typst 写作
cd new_path
code .

# 运行预览
kodama serve

# 构建代码
kodama build
```

### Template

[+](/regulations/markdown-template.md#:embed)

[+](/regulations/typst-template.md#:embed)
