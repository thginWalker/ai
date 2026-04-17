---
title: 如何写hexo博客
date: 2026-02-23 19:03:28
tags: 其他
categories: Hexo教程
---
## 前言

第一次使用hexo+github page搭建网站已经是2018年了，时间如白驹过隙转瞬即逝。此刻已经是2026年了。笔者经历了很多，也有诸如感悟，此刻更加明白沉淀积累的重要性，因此希望继续使用博客进行相关技术积累。

## hexo命令

发布新的博文，使用命令：

```bash
hexo new "My New Post"
```

单篇文章添加相关内容信息：

```bash
---
title: 如何写hexo博客
date: 2026-02-23 19:03:28
tags: 其他
tags:
  - RNN
  - LSTM
  - RNN
categories: Hexo教程
---
```

运行本地服务器查看：

```bash
hexo server # hexo s
```

由markdowon文件生成静态页：

```bash
hexo generate # hexo g
```

部署到远程github page页中：

```bash
hexo delopy # hexo d
```

单条生成及部署命令：

```bash
hexo clean && hexo generate && hexo deploy
```

## 后记

无论如何继续学习，不能停止学习！
