# Leo的个人博客

读书生涯迟暮，终于决定开设个人博客。

## 简介

这是一个使用Jekyll构建的个人博客，用于分享知识、记录见闻、欣赏风景。

## 内容分类

- **知识分享**：技术学习笔记、读书心得、思考总结
- **生活见闻**：日常观察、人生感悟、经验分享
- **沿途风景**：旅行游记、摄影作品、美景记录

## 本地运行

如果你想在本地运行这个博客：

1. 安装Jekyll和相关依赖：
   ```bash
   gem install jekyll bundler
   ```

2. 克隆仓库：
   ```bash
   git clone https://github.com/LiChuanchao-Leo/Leo.github.io.git
   cd Leo.github.io
   ```

3. 安装依赖：
   ```bash
   bundle install
   ```

4. 本地运行：
   ```bash
   bundle exec jekyll serve
   ```

5. 在浏览器中访问 `http://localhost:4000`

## 添加新文章

在 `_posts` 目录下创建新的Markdown文件，文件名格式为 `YYYY-MM-DD-title.md`，例如：

```markdown
---
layout: post
title: "文章标题"
date: 2024-01-01 10:00:00 +0800
category: 知识分享
author: Leo
---

文章内容...
```

## 部署

本博客使用GitHub Pages自动部署。推送到main分支后，GitHub会自动构建并部署网站。

## 许可

本博客内容采用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 许可协议。
