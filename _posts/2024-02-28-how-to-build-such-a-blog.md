---
layout: post
title: 如何搭建这样的一个blog
subtitle: 记录并分享如何搭建这样一个blog的过程
gh-repo: guoqifeng/guoqifeng.github.io
gh-badge: [star, fork, follow]
tags: [blog] 
comments: true
author: 郭其峰
---

{: .box-success}
很早之前就想搭建一个简单的博客网站，用来记录技术学习中的点点滴滴。现在终于在github上通过github pages功能实现低成本的方案，并且接入到了我自己的域名中去了。不得不说，看着自己域名的网站能够在外网展示确实是一件很有成就感的事情。

# 如何搭建这样的一个blog

## 方案

之前我采用的腾讯云服务器+wordpress方案，不过这个方案需要购买腾讯云服务器，并且由于wordpress的编辑比较难上手，作为一个后端程序员，弄出一个页面是可能的，不过要弄得好看一点就很麻烦了。雪上加霜是之前折扣购置的腾讯云服务器（1C1G）需要续费，而且部署的wordpress服务出现了白屏，一时半会也解决不了。索性放弃自建服务器的方案，将内容和服务都托管到github pages上，形成现在的github pages + jekyll + markdown的方案。

小结一下，自建服务器需要租服务器费用，而且wordpress对编辑不太友好，并且如果服务器在大陆的话，需要进行工信部和公安备案，流程比较长。而github pages 可以免费使用github的服务器，同时可以加上自己的域名地址，不过服务器在海外，访问速度就随缘了。考虑到自己购买的腾讯云的配置也没有高到哪里去，这一点也可以接收。

## 技术

github pages 的使用可以参考github官方文档，而jekyll本来我是要用官方的方法本地生成的，但是我的本地机器安装jekyll的工具不成功，于是变通一下，从github上找了一个开源的模板，就是你们现在看到的这个 [beautiful-jekyll](https://github.com/daattali/beautiful-jekyll),他的项目readme中有完整的fork，修改和发文方式，可以自行观看。

