<table><tr><td bgcolor=#e2dede style="text-algin:center">本渣渣不专注技术，只专注使用技术，不是一个资深的coder，是一个不折不扣的copier</td></tr></table>


<table><tr><td bgcolor=darkgreen><font color=white>零基础，完整的项目，基于最新版 Django 1.11 和 Python 3.6。带你从零开始一步步开发属于自己的博客网站，让你亲身体验 Python web 开发之便捷，从新认识 Django 开发。</font></td></tr></table>



本博主最初接触 Python 是从网站开发开始，单纯的只是想有一个个人网站来装B，据说 Python 开发网站快速便捷，信以为真，就这样开始了 Python 之旅。学习 Python 也已经有一年之久，现在也从事 Python 相关工作，最初拥有个人网站的想法至今未实现。

并不是本渣渣，没有开发一个网站的能力，只是因为开发不出来自己喜欢的前台页面。跟着别人的教程，也开发过两个个人博客网站，但是由于界面太丑，JS、HTHL、CSS等技术也只是简单了解，没有修改前台的能力。

最近，发现 CSDN 越来越像一个营销网站，不断的在迎合百度。这一现状又让我产生了开发个人博客网站的想法。但是目前从事的是 Python 后端开发，前端技术还是没有长进。

<h3>怎么办？</h3>



在最近学习爬虫的过程中，发现了崔庆才个人博客网站，被崔大佬博客首页的动态轮播图吸引了。感觉自己想拥有一个这样的网站，接着就迫不及待的右击鼠标打开了网站源码，经过查看发现，此网站是通过 Wordpress 搭建的。了解后发现，Wordpress 是使用 PHP 语言开发的博客平台，用户可以在支持 PHP 和 MySQL 数据库的服务器上架设属于自己的网站。

与此同时发现有很多 Wordpress 主题，页面可以多样多彩，竟然还有专业开发售卖 Wordpress 主题的。作为码农的我怎么可能会去买这些主题，那还不是，只要你上线，这个主题就属于我的节奏。

就这样，给我开发个人博客一个很好的灵感，就是抄前端。可能有人会疑惑，网站前端不是都可以抄吗？为什么非要抄 Wordpress 呢？

这个很好理解，你去了解一下 Wordpress 就知道怎么回事了,看一下百度百科即可

[Wordpress百度百科](https://baike.baidu.com/item/WordPress/450615?fr=aladdin)

<h3>Wordpress 其中有两个优势是我看中的</h3>

1、适合 DIY，如果你是喜欢丰富内容的网站，那么 Wordpress 可以很好地符合你的胃口。

2、主题很多，网站上一大片都是 Wordpress 的主题，各色各样，应有尽有！

由于它是一个框架，那么对应的主题开发一定是相当规范，适合 DIY。这意味着什么知道吗？你只要在哪里看到一个 Wordpress 搭建的网站，发现哎呦某一个功能非常炫酷，哎呦，这个主题适合 我的口味。那么好了，这个网站就是你的了，不用写任何的 JS 、 HTML、 CSS 代码，直接用 Python Web 框架渲染数据就完事。

搞过 Python Web 开发的小伙伴可能已经想到哪个 Web 框架最适合了，没错就是 Django 框架

比较流行的几个 Python Web 框架了解一下

[Django百度百科](https://baike.baidu.com/item/django/61531?fr=aladdin) &ensp;&ensp;&ensp;&ensp; [Flask百度百科](https://baike.baidu.com/item/Flask/1241509?fr=aladdin) &ensp;&ensp;&ensp;&ensp;   [Tornado百度百科](https://baike.baidu.com/item/Tornado/13779735?fr=aladdin) &ensp;&ensp;&ensp;&ensp; [Web.py百度百科](https://baike.baidu.com/item/web.py/10037145?fr=aladdin) &ensp;&ensp;&ensp;&ensp; [Quixote百度百科](https://baike.baidu.com/item/Quixote/9370167)


[Quixote百度百科](https://baike.baidu.com/item/Quixote/9370167)  并不流行，只不过豆瓣就是基于此开发的

<h3>结合 Wordpress 让 Django 开发从未变得如此简单</h3>

了解一下就可以发现 Django 是最流行的。不管流不流行，我看重的是 Django 的是高集成性、和它的模板机制

Django 将 MVC 中的视图进一步分解为 Django 视图 和 Django 模板两个部分，分别决定 "展现哪些数据" 和 "如何展现"，使得 Django 的模板可以根据需要随时替换，而不仅仅限制于内置的模板。这样就可以配合，Wordpress 主题随意生产自己喜欢的网站。如果你是刚接触 Dajngo 可能听的有点迷糊，不要急躁。那是因为你还不了解 Django  MVT 模式的工作机制，跟着我的指引，当你了解了 Django 的工作原理，你就会发现，搭建一个网站如此简单，而且，不需要生产代码，只需要做一个代码的搬运工即可实现个人博客网站的搭建。

不再有看完一个视频教程，或者图文教程，而在脑海中没有一个独立建站的概念。这里教你的是搬运代码，使用代码，而不是看着教程敲代码。让你脑海中有一个独立建站的步骤。让你具备看到一个喜欢的网站前端一周内实现据为己有的能力，不仅仅如此，还要有给自己网站添加任何自己喜欢的功能的能力。讲道理我在学习 Python Web 时就有看到好看的网站，想自己搞一个，但是又不知道怎么整的无奈，最近花了半个月的时间，研究了这么一个，使用 Wordpress 主题 + Django 后台 随意搭建个人博客的模式

[网站在线效果](http://stormsha.cn/) &ensp;&ensp; 或者 &ensp;&ensp; [网站在线效果](http://stormsha.com/)

![图片效果](http://stormsha.cn/static/images/pcindexshow.png)

网站源码已经托管于 Github 欢迎 Fork 学习，如果有什么好的功能和改进想法，让这个模式变得更加方便实用
本渣渣会持续升级维护此项目，目标让它变成人人可使用的博客模板

[网站源码](https://github.com/stormsha/blog)







