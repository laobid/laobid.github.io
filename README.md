# 老毕登的博客

基于 [Fuwari](https://github.com/saicaca/fuwari) 主题（Astro）的个人博客。
源码在 GitHub，托管在 Vercel。

## 怎么写一篇新文章

在 `src/content/posts/` 下新建一个 `.md` 文件，开头写：

```markdown
---
title: 文章标题
published: 2026-11-01
description: 一句话简介，会显示在列表里
tags: [标签1, 标签2]
category: 分类
draft: false
---

正文内容，正常写 Markdown 即可。
```

## 本地预览

```bash
pnpm install     # 只在第一次需要
pnpm dev         # 打开 http://localhost:4321
```

## 构建

```bash
pnpm build       # 产物在 dist/
```

## 站点配置

改 `src/config.ts`：标题、副标题、语言、主题色、横幅、导航栏、个人资料卡。

- 头像：`src/assets/images/avatar.png`
- 横幅：`src/assets/images/banner.png`

## 部署

推送到 `main` 分支后，Vercel 会自动构建并上线，无需手动操作。

## 版权

主题 Fuwari 采用 MIT 协议，版权归 [saicaca](https://github.com/saicaca) 所有。
