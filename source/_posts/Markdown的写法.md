---
title: Markdown的常用写法
date: 2018-11-21 22:08:11
categories:
- hexo博客技术
tags:
- Markdown
keywords: Markdown,写法
description:
copyright:
banner_img: https://github.com/zhouhengheng0705/zhouhengheng0705.github.io/blob/master/Markdown%E7%9A%84%E5%86%99%E6%B3%95/wallhaven-314029.png?raw=true
---
<font size="4"><strong>hexo博客的文章都是用Markdown格式编写的，所以要想熟练的编写hexo博客的话，一些常用的格式还是需要了解一下的，本篇介绍几个常用的Markdown写法，有兴趣的小伙伴们可以学习一下。</strong></font><br/>
!["Markdown"](https://github.com/zhouhengheng0705/zhouhengheng0705.github.io/blob/master/Markdown%E7%9A%84%E5%86%99%E6%B3%95/super_mario_history-wallpaper-960x600.jpg?raw=true)
<!--more-->

<font size="4"><strong>1.列表</strong></font>

```
例:
 - The Beatles
  - Atom
    - git

※注意:「-」和文字之间有半角空格。

```

<font size="4"><strong>2.标题</strong></font>

```
例:
# 标题1
## 标题2
### 标题3

※注意:「#」和文字之间有半角空格。
```

<font size="4"><strong>3.强调</strong></font>

```
例:
**Hello World**
```

<font size="4"><strong>4.引用</strong></font>

```
例:
> Beautiful is better than ugly.

※注意:「>」和文字之间有半角空格。
```

<font size="4"><strong>5.链接</strong></font>

```
例:
[我的博客](http://www.zhouhengheng.com)
```

<font size="4"><strong>6.取消线</strong></font>

```
例:
~~取消~~
```


<font size="4"><strong>7.水平线</strong></font>

```
格式: 从「>」，「_」，「*」中任意并列三个以上

例:
---
___

***
```

<font size="4"><strong>8.插入图片</strong></font>

```
格式: ![代替文字](图片URL “标题”)」）

例:

![名片工厂图片](https://meishi.artisj.com/summary/image/logo.gif "名片工厂")
```


<font size="4"><strong>9.段落和改行</strong></font>

```
段落空一整行。
改行空两个半角空格以上。

例:

你学会使用Markdown格式了吗？

只会一点，
还在学习中。

```

<font size="4"><strong>10.段首空格/段首缩进</strong></font>
```
格式:
&nbsp;//半角空格
&emsp;//全角空格

例:

&emsp;我叫张三。&nbsp;我喜欢学习和分享。

```

<font size="4"><strong>11.代码引用</strong></font>


①指定开发语言时

例:

\`\`\`python

def hello_world():
    print('Hello world!')

hello_world()

\`\`\`

②未指定开发语言时

例:

\`\`\`

print('Hello world!)

\`\`\`
