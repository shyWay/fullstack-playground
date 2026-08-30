# Fullstack Playground

用于存放个人开发实验、小工具和兼职项目代码的仓库。

## 文案卡片生成器

一个免费、无需登录的浏览器小工具。输入文字并选择喜欢的背景色，即可生成带有毛玻璃质感的 Ins 风文字卡片，并下载为高清 PNG 图片。

在线体验：[打开文字卡片生成器](https://shyway.github.io/fullstack-playground/)

### 功能

- 实时编辑卡片文字，支持换行排版
- 提供 8 组渐变背景配色，并支持自定义主色与辅色
- 可选择衬线、无衬线或手写感字体
- 支持左对齐、居中和右对齐
- 内置随机文案与配色灵感
- 一键导出 1600 × 1600 高清 PNG 卡片
- 纯前端实现，不会上传或保存用户输入的内容

### 本地使用

克隆仓库后，直接用浏览器打开 `copywriting-card-generator/index.html` 即可使用；不需要安装依赖或启动后端服务。

```bash
git clone git@github.com:shyWay/fullstack-playground.git
cd fullstack-playground
open copywriting-card-generator/index.html
```

### 目录结构

```text
fullstack-playground/
└── copywriting-card-generator/
    └── index.html
```

### 免费发布

该工具通过 GitHub Pages 免费托管，并使用 HTTPS 提供公开访问。

## License

本仓库采用 [Apache License 2.0](LICENSE)。
