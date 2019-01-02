---
title: Hexo添加菜单
date: 2018-12-27 22:43:59
categories:
- hexo博客技术
tags:
- javascript
- CSS
- html
- Markdown
keywords: Hexo,Menu
description:
copyright:
banner_img: https://github.com/zhouhengheng0705/zhouhengheng0705.github.io/blob/master/Hexo%E6%B7%BB%E5%8A%A0%E8%8F%9C%E5%8D%95/maldives.jpg?raw=true
---
<font size="4"><strong>本篇文章介绍在Hexo的Next主题下新添加一个"学习"的菜单分类。</strong></font><br/>
!["添加菜单"](https://github.com/zhouhengheng0705/zhouhengheng0705.github.io/blob/master/Hexo%E6%B7%BB%E5%8A%A0%E8%8F%9C%E5%8D%95/spider_man_into_the_spider_verse_4k-wallpaper-960x600.jpg?raw=true)
<!--more-->
<font size="4"><strong>新建一个页面，命名为</strong></font><font color="red">study</font>
```
$ hexo new page "study"
```

此时会在\source文件夹中生成一个study的新文件夹

<font size="4"><strong>编辑study文件下的md页面</strong></font>

将类型设置为study,主题将自动生成study这个分类。

```
title: 学习
date: 2017-12-14 13:05:38
type: "study"
---
```
如果有启用多说或者Disqus评论，默认页面也会带有评论。需要关闭的话，请添加字段comments并将值设置为false，如：

```
title: 学习
date: 2017-12-14 13:05:38
type: "study"
comments: false
---
```
<font size="4"><strong>在菜单中添加图标和链接</strong></font>

编辑主题的<font color="red">_config.yml</font>，在其中的<font color="red">menu</font>中添加如下：

```
menu:
  study: /study/ || heartbeat
```

<font size="4"><strong>新添加的菜单需要翻译对应的中文</strong></font>
打开<font color="red">theme>next>languages>zh-Hans.yml</font>，在menu下添加

```
menu:
  home: 首页
  archives: 归档
  categories: 分类
  tags: 标签
  about: 关于
  search: 搜索
  study: 学习
  read: 读书
  sitemap: 站点地图
```

<iframe width="560" height="315" src="https://www.youtube.com/embed/SI_mGJQt5g0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
