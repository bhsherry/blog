---	
layout: post	
title: 使用 GitPage 搭建个人博客	
categories: 建站	
description: 使用 GitPage 搭建个人博客	
keywords: 建站, GitPage, GitHub	
---	

# 使用 GitPage 搭建个人博客 - 简书

本文主要介绍词博客的搭建过程。从小白做起

*   `Gitpage`：`GitHub` 提供的开发者可以拥有个人域名
*   `jekyll`：博客模板，快速搭建博客必备
*   `GitTalk`：博客评论模块，评论信息保存在 `issue` 中， 方便查看

申请 GitHub 账号
------------

点击[这里](https://github.com/)，注册一个账号，已有 `GitHub` 账号的跳过

新建一个项目
------

使用注册的账号登陆，在[这里](https://github.com/new)新建一个项目

![](https://upload-images.jianshu.io/upload_images/1218612-6b239b4d8f615b1f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1000/format/webp)

新建项目.png

使用 `Gitpage`
------------

新建成功之后在项目首页，点击 `Settings -》GitHub Pages`，

![](https://upload-images.jianshu.io/upload_images/1218612-4d37e354d0948978.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/741/format/webp)

image.png

此时已经有个一个相当于个人网站的东西，图中绿色部分的地址点击即可访问

`Choose a theme` 按钮可以帮你选择一个网站主题

寻找模板
----

[这里](http://jekyllthemes.org/)有很多模板

我推荐的一套，也是我自己使用的一套：[https://github.com/mzlogin/mzlogin.github.io](https://github.com/mzlogin/mzlogin.github.io)

使用模板
----

使用模板就是将你刚才下载的模板上传到你的项目中，你可以直接使用自己的喜欢的工具，或者使用接下来讲述的 `Git Desktop`

### 使用 `Git Desktop`

下载地址

*   Mac：[https://mac.github.com/](https://mac.github.com/)
*   Win：[https://windows.github.com/](https://windows.github.com/)

安装之后的界面如下

![](https://upload-images.jianshu.io/upload_images/1218612-56e59f8db47ff944.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/953/format/webp)

Git Desktop.png

其中

*   ① 新安装的这里应该是添加按钮，如果不是的话，就 `File -> Clone Repository`

![](https://upload-images.jianshu.io/upload_images/1218612-78798e8a4edbb5f7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/429/format/webp)

image.png

*   ② 选择分支
*   ③ 将新下载的项目直接复制到刚才 `Clone` 下来的文件夹之后，在 `⑤` 写上提交的日志，任意写，然后点击提交
*   ④ 点击 `push` 到远程

发表文章
----

在 `_post` 文件夹中新增 `md` 文件即可，完了记得提交至仓库

1.  [傻瓜都可以利用github pages建博客](http://cyzus.github.io/2015/06/21/github-build-blog/)
2.  [码志](https://github.com/mzlogin/mzlogin.github.io)
3.  jekyll：[https://www.jekyll.com.cn/](https://www.jekyll.com.cn/)
4.  GitTalk：[https://github.com/gitalk/gitalk](https://github.com/gitalk/gitalk)