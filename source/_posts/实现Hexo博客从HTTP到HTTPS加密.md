---
title: 实现Hexo博客从HTTP到HTTPS加密
date: 2019-01-01 21:37:35
categories:
- hexo博客技术
tags:
- https
- CloudFlare
keywords:
description:
copyright:
banner_img: https://github.com/zhouhengheng0705/zhouhengheng0705.github.io/blob/master/%E5%AE%9E%E7%8E%B0Hexo%E5%8D%9A%E5%AE%A2%E4%BB%8EHTTP%E5%88%B0HTTPS%E5%8A%A0%E5%AF%86/wallhaven-353314.png?raw=true
---
<font size="4"><strong>本篇文章介绍如何将http的Hexo博客升级为加密的https网站。</strong></font><br/>
!["加密"](https://github.com/zhouhengheng0705/zhouhengheng0705.github.io/blob/master/%E5%AE%9E%E7%8E%B0Hexo%E5%8D%9A%E5%AE%A2%E4%BB%8EHTTP%E5%88%B0HTTPS%E5%8A%A0%E5%AF%86/black_hole_on_earth-wallpaper-960x600.jpg?raw=true)
<!--more-->
想必玩hexo博客的小伙伴们，都想把自己http网站升级成拥有加密传输的https网站。好处大致有三个，一是为了增加数据传输安全，二是谷歌百度等搜索都优先收录https网站，所以能一定程度上提高SEO排名，最后我认为有把小绿锁，能增加心里成就感。
废话不多说，直接进入正题。如何将http的Hexo博客升级为加密的https网站？

<font size="4"><strong>通过CloudFlare实现Hexo博客的HTTPS加密</strong></font><br/>

cloudflare 是一家国外的CDN加速服务商，向客户提供网站安全管理、性能优化及相关的技术支持为主要业务。通过基于反向代理的内容分发网络(CDN, Content Delivery Network)、任播(Anycast)技术、基于nginx+lua架构的Web应用防火墙(WAF, Web Application Firewall)及分布式域名解析服务(Distributed Domain Name Server)等技术，Cloudflare可以帮助受保护站点抵御包括分布式拒绝服务攻击(DDoS, Distributed Denial of Service)在内的大多数网络攻击，确保该网站长期在线，同时提升网站的性能、访问速度以改善访客体验。<br/>
首先，在[CloudFlare的官网](https://dash.cloudflare.com/)注册一个CloudFlare账号并把添加自己的域名，点击下图中的DNS项目。
!["CloudFlare1"](https://github.com/zhouhengheng0705/zhouhengheng0705.github.io/blob/master/%E5%AE%9E%E7%8E%B0Hexo%E5%8D%9A%E5%AE%A2%E4%BB%8EHTTP%E5%88%B0HTTPS%E5%8A%A0%E5%AF%86/CloudFlare1.jpg?raw=true)

然后，点击下图中红圈内的「Add Record」按钮，添加如图中的两条记录，Type都选「CNAME」,Name一个填自己的域名，另外一个填WWW，Value都填github上托管的GitHub Pages地址，即<font color="red">your-github-username.github.com</font>这样的形式。
!["CloudFlare2"](https://raw.githubusercontent.com/zhouhengheng0705/zhouhengheng0705.github.io/master/%E5%AE%9E%E7%8E%B0Hexo%E5%8D%9A%E5%AE%A2%E4%BB%8EHTTP%E5%88%B0HTTPS%E5%8A%A0%E5%AF%86/CloudFlare2.jpg)





<script type="text/javascript" src="/js/src/bai.js"></script>
