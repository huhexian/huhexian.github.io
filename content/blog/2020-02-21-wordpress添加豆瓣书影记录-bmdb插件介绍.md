---
title: WordPress添加豆瓣书影记录——bmdb插件介绍
author: 青山
type: post
date: 2020-02-21T13:48:15+00:00
url: /2866.html
head_img_url:
  - 
  - 
post_copyright:
  - 1
  - 1
toc:
  - 0
  - 0
seo_title:
  - 
  - 
seo_manual_keywords:
  - 0
  - 0
seo_manual_des:
  - 0
  - 0
suxing_ding:
  - 4
  - 4
baidu_record:
  - 1
  - 1
zm_like:
  - 1
  - 1
views:
  - 1485
rank_math_news_sitemap_robots:
  - index
rank_math_robots:
  - 'a:1:{i:0;s:5:"index";}'
rank_math_analytic_object_id:
  - 115
categories:
  - 玩物志
tags:
  - WordPress
  - 豆瓣

---
<figure class="wp-block-image size-large"><a href="http://yinji.org/wp-content/uploads/2020/06/2020060911012597-scaled.jpg" loading="lazy" rel="sponsored" data-fancybox="gallery"><img decoding="async" src="http://yinji.org/wp-content/uploads/2020/06/2020060911012597-1170x730.jpg" class="wp-image-3058"/ alt="WordPress添加豆瓣书影记录——bmdb插件介绍 - 第1张图片" title="WordPress添加豆瓣书影记录——bmdb插件介绍 - 第1张图片 | 印记" ></a></figure> 

介绍一款一条龙全自动添加豆瓣书影记录的插件。该插件为<a class="url" href="https://bearye.cn/" rel="external nofollow ugc">熊野</a>在基于牧风的项目上开发的WordPress插件。

在该页面申请Secret：<a href="https://bm.weajs.com/" target="_blank" rel="noreferrer noopener" aria-label="（在新窗口打开）">https://bm.weajs.com/</a>另外还需要填写你的豆瓣id及昵称，在该网站可同步豆瓣平台标注的电影和书籍信息，也可以在上面标注电影。

下一步即是安装插件，填写好secret即可。新建页面并填入

[bm db]movies[/bm db]或[bm db]books[/bm db]&nbsp; &nbsp;（使用时请删去空格）

作者的话：WordPress 自带 jQuery 并不支持 $ 关键字，head 设置 meta 也需要通过官方钩子实现，如果你想在自己的 WordPress 的站点上布置读书观影记录，并不能完全按照牧风的教程来做，对没有接触过编程的人来说，这存在一定难度。

下载地址：<a href="https://github.com/ibearye/bmdb-for-wordpress" rel="nofollow">https://github.com/ibearye/bmdb-for-wordpress</a>

牧风的项目地址：<a href="https://github.com/iMuFeng/bmdb/" target="_blank" rel="nofollow noopener noreferrer">https://github.com/iMuFeng/bmdb/</a>

效果演示：[阅读记录][1] [观影记录][2]

作者也介绍了集成到主题的方法。一并转载参考。

## 集成到主题 {.wp-block-heading}

在wordpress上布置bmdb，核心基本与Github上的readme没区别，特别就在于如何在wordpress上正确

  1. 设置头部meta；
  2. 引入资源文件。

第一点，设置头部meta，在&nbsp;`functions.php`&nbsp;添加代码：

<pre class="wp-block-code"><code>function bmdb_head()
{
    echo '&lt;meta name="referrer" content="never">';
}
add_action('wp_head','bmdb_head');</code></pre>

第二点，引入资源，在&nbsp;`functions.php`&nbsp;添加代码：

<pre class="wp-block-code"><code>function bmdb_css_js(){
    wp_enqueue_script("jquery");//如果已引入jquery，就去掉这一行代码
    wp_enqueue_style( 'bmdb', get_template_directory_uri().'/dist/Bmdb.min.css' );//第二个参数填css的地址
    wp_enqueue_script( 'bmdb', get_template_directory_uri().'/dist/Bmdb.min.js' );//第二个参数填js的地址
}
add_action('wp_enqueue_scripts', 'bmdb_css_js');</code></pre>

如果你直接把Github上下载的dist文件夹扔到了主题文件夹里，上面的代码就不用改了。

这两点解决了其他就很简单了，没必要再说了。

 [1]: http://yinji.org/book.html
 [2]: http://yinji.org/movie.html