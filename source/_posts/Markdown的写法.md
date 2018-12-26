---
title: Markdown的常用写法
date: 2018-11-21 22:08:11
tags:
banner_img: https://github.com/zhouhengheng0705/zhouhengheng0705.github.io/blob/master/images/bumblebee.jpg?raw=true
---
!["Markdown"](Markdown的写法/Markdown.png)
<!--more-->
hexo博客的文章都是用Markdown格式编写的，所以要想熟练的编写hexo博客的话，一些常用的格式还是需要了解一下的，下面我列举了几个常用的写法，有兴趣的小伙伴们可以学习一下。

<font color="ff0000">1.列表</font>

```
例:
 - The Beatles
  - Atom
    - git

※注意:「-」和文字之间有半角空格。

```

<font color="ff0000">2.标题</font>

```
例:
# 标题1
## 标题2
### 标题3

※注意:「#」和文字之间有半角空格。
```

<font color="ff0000">3.强调</font>

```
例:
**Hello World**
```

<font color="ff0000">4.引用</font>

```
例:
> Beautiful is better than ugly.

※注意:「>」和文字之间有半角空格。
```

<font color="ff0000">5.链接</font>

```
例:
[我的博客](http://www.zhouhengheng.com)
```

<font color="ff0000">6.取消线</font>

```
例:
~~取消~~
```


<font color="ff0000">7.水平线</font>

```
格式: 从「>」，「_」，「*」中任意并列三个以上

例:
---
___

***
```

<font color="ff0000">8.插入图片</font>

```
格式: ![代替文字](图片URL “标题”)」）

例:

![名片工厂图片](https://meishi.artisj.com/summary/image/logo.gif "名片工厂")
```


<font color="ff0000">9.段落和改行</font>

```
段落空一整行。
改行空两个半角空格以上。

例:

你学会使用Markdown格式了吗？

只会一点，
还在学习中。

```

<font color="ff0000">10.代码引用</font>


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
