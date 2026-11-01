---
title: 你好，世界
published: 2026-11-01
description: 博客开张第一篇，说说这个站点是怎么来的。
image: ""
tags: [随笔, 开始]
category: 随笔
draft: false
---

这是这个博客的第一篇文章。

## 为什么开这个博客

想有个地方能把自己学到的东西、遇到的问题、想到的碎碎念存下来。社交平台太吵，文档又太正式，博客刚好。

## 这个博客是怎么搭的

整套东西都是托管方案，不需要服务器：

| 部分 | 用什么 |
| :--- | :--- |
| 文章存储 | GitHub 仓库里的 Markdown 文件 |
| 网站构建 | Astro（把 Markdown 变成网页） |
| 托管上线 | Vercel（自动构建、自动 HTTPS、免费） |

写文章的流程也简单：新建一个 `.md` 文件，写好内容，提交到 GitHub，网站一分钟后自动更新。

## 一些约定

> 会写技术笔记，也会写日常。技术笔记尽量写清楚“为什么”，不只写“怎么做”。

::github{repo="saicaca/fuwari"}

## 接下来的计划

- [x] 把站搭起来
- [ ] 把以前的学习笔记整理上来
- [ ] 折腾一下主题配色和字体
- [ ] 也许是买个好记的域名

---

**代码块长这样：**

```js title="hello.js" showLineNumbers
function hello(name) {
  // Fuwari 支持 Expressive Code，代码块可以带文件名和行号
  console.log(`你好，${name}！`);
}

hello("世界");
```

就写到这里，第一篇先这样。
