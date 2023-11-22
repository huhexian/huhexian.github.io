---
title: "关于我的博客"
date: 2021-02-06T09:55:32+08:00
slug: about my blog
tags:
- 博客
- WordPress
cover:
    image: "" # 封面圖片路径 (ex:clear-301-redirection-cache-chrome/cover.jpg)
    caption: "" # 封面圖片底部描述
    alt: ""
    relative: false
---

之前在网上看到过这样一句话：**当你不知道该写什么的时候就写如何搭建博客**。不过，我这篇不是要讲如何搭建，而是介绍下我博客的相关信息。因为经常会有网友给我留言，问我博客是什么程序、什么主题，用的什么服务器之类的问题，今天就整理下。

|博客程序|[WordPress](https://cn.wordpress.org/)|
|---------|-------------------------------------|
|博客主题|[Twenty Twelve](https://cn.wordpress.org/themes/twentytwelve/)|
|域名|[腾讯云](https://dnspod.cloud.tencent.com/)|
|服务器|[腾讯云](https://cloud.tencent.com/act/campus)（学生机）|
|域名解析|[DNSPod](https://www.dnspod.cn/)|
|服务器面板|[宝塔面板](https://www.bt.cn/)|

博客基本的信息就是表格里所示。现在详细说一说。

## 服务器 
其实如果对个人博客要求不高的话，简单的虚拟主机就可以满足。2018年我刚开始建博客的时候用的就是虚拟主机，从**[老薛主机](http://husay.cc/lxzj.html)**，到**网硕互联**，最后才到**腾讯云**的学生机。服务器可以折腾很多东西，不喜欢折腾只想简简单单写博客的，虚拟主机是最好的选择。

对于服务器，如果你是25岁以下的用户，你可以享受腾讯云和阿里云的学生优惠，对付一个博客足够了；如果不是，腾讯云和阿里云也有实惠套餐供你选择。国内服务器推荐阿里云和腾讯云，国外服务器没用过，不做推荐。

对于虚拟主机，**[篱落主机](https://my.liluohost.com/aff.php?aff=21)**、**老薛主机**、**[衡天主机](https://my.hengtian.cc/aff.php?aff=3731)**、**[恒创主机](http://husay.cc/hczj.html)**，价格实惠，配置较好，可以尝试。 

## 域名 
域名不建议选择非主流域名，我博客第一个域名是 men 后缀：longest.men，取“最长的男人”之意，现在用的 com 域名都是在网硕互联买虚拟主机的时候赠送注册的。

是否备案取决自己，各有各的好处。已备案的域名可以享受国内服务器/虚拟主机和CDN服务，速度较快，但是多多少少会受到约束；未备案的域名只能使用大陆以外地区的服务器/虚拟主机，约束少，但速度会受到影响。

com/cn/net可以考虑首选，me做个人博客域名很适合。域名注册平台，国内可以选择[新网](http://www.xinnet.com/)、[万网](https://wanwang.aliyun.com/)(阿里云)、[西部数码](https://www.west.cn/)、[趣域](https://www.quyu.net/)……国外平台可以选择 [Namecheap](https://www.namecheap.com/)、[GoDaddy](https://sg.godaddy.com/zh)(狗爹)、[NameSilo](https://www.namesilo.com/)、[Dynadot](https://www.dynadot.com/)、[Porkbun](https://porkbun.com/)……另外推荐域名比价平台：[哪煮米](https://www.nazhumi.com/)、[NameBeta](https://namebeta.com/)。 

## 程序 
前前后后用过 [**WordPress**](https://cn.wordpress.org/)、[**Typecho**](http://typecho.org/)、[**zblog**](https://www.zblogcn.com/)、[**emlog**](https://www.emlog.net/)，最后觉得 WordPress 更上手，生态强大，可操作性强，容易折腾，功能也比较完善。尽管有人觉得它过于臃肿，加载较慢，但看看我博客，慢吗？当然方案也不止这一种。

静态博客也是一个不错的选择，例如 [**Hexo**](https://hexo.io/zh-cn/)、[**Gridea**](https://gridea.dev/)、[**Jekyll**](http://jekyllcn.com/)、[**Hugo**](https://www.gohugo.org/)……这些皆可搭配 **[Github](https://github.com/)**、**[Coding](https://coding.net/)**，再配上免费的二级域名，无成本即可搭建一个博客，我不太了解，网上教程很多，自行搜索即可。 

## 插件 
在插件方面，我一向就是能用代码尽量不用插件。
- **[commonWP](https://cn.wordpress.org/plugins/commonwp/)** 
- **[Comet Cache](https://wordpress.org/plugins/comet-cache/)** 
- **twentytwelve 主题功能增强** 
- **[积木箱子](https://www.nicetheme.cn/nicetheme-plugins-store.html)** 
- **[豆瓣读书观影记录](http://husay.cc/2866.html)** 

第一个用来缓存博客后台相关文件，第二个类似 WP Super Cache ，第三个插件是我基于 [**沙唐桔**](https://cyhour.com/) 制作的主题增强插件，在他的代码基础上加了别的功能。并且采用 [**ZWWoOoOo**](https://zww.me/wordpress-archive-page-template-wp-primary-function-2014-edition.z-turn) 的文章归档教程制作了 **[归档页面](http://husay.cc/archives.html)** 。用 **[豆瓣读书观影记录](http://husay.cc/2866.html)** 制作了两个页面：[**阅读记录**](http://husay.cc/book.html)、[**观影记录**](http://husay.cc/movie.html)。主题css方面稍微修改了，具体修改在哪，自行查看源代码并对比原版主题即可。 

## 主题 
个人博客的话，官方的主题基本能满足需求。例如我现在用的 Twenty Twelve，过去使用的 Twenty Fifteen，各有特色。诸如此类的免费主题还有很多，各大主题聚合站基本都有；付费主题作者推荐：[**nicetheme**](https://www.nicetheme.cn/)、[**XinTheme**](https://www.xintheme.com/)，主题质量和售后服务蛮不错。 

## 优化 
建议的优化方案是配置 CDN，开启动静分离，但我没这么做，太复杂了，我折腾容易出错。于是我就在服务器方面进行了优化。使用 Memcached 缓存数据库加速 WordPress 网站；使用 Comet Cache 静态缓存插件。在主题方面，简化代码、屏蔽没用的功能，这些用上面提到的 **twentytwelve 主题功能增强** 插件就可以做到。CDN 推荐[**七牛云**](https://www.qiniu.com/)、[**又拍云**](https://www.upyun.com/)、[**腾讯云**](https://cloud.tencent.com/product/cdn)、[**阿里云**](https://www.aliyun.com/product/cdn)，如果是国外服务器，则推荐 [**Cloudflare**](https://www.cloudflare.com/)。 

## RSS阅读 
这方面主要有两个方案：自己建的和第三方平台。 
- 自建 RSS 主要推荐：[**蚁阅**](https://rss.anyant.com/)、Tiny Tiny Rss 
- 第三方平台推荐：Inoreader、Feedly、RSS 追踪 可以参考我以前的文章： 
- [RSS追踪：Windows平台上一款好用的RSS阅读器](http://husay.cc/3363.html) 
- [我还是更喜欢这样的RSS阅读](http://husay.cc/3249.html) 

上述所列的仅供参考，具体使用还得看个人。 我的博客马上三周年，写了近三年，用了 WordPress 近三年，多多少少也有点经验，今天写出来权当分享经验，如有错误，欢迎指正。 如果对博客建设方面还有问题，欢迎[联系](http://husay.cc/contact.html)我。