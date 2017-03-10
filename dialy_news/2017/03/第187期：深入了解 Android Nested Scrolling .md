# 第187期：深入了解 Android Nested Scrolling 

## 深度讨论

[深入了解 Android Nested Scrolling ](https://www.diycode.cc/news/2101)

Android常规的Touch事件传递机制是自顶向下，由外向内的，一旦确定了事件消费者View，随后的事件都将传递到该View。因为是自顶向下，父控件可以随时拦截事件，下拉刷新、拖拽排序、折叠等交互效果都可以通过这套机制完成。Touch事件传递机制是Android开发必须掌握的基本内容。但是这套机制存在一个缺陷：子View无法通知父View处理事件。NestedScrolling就是为这个场景设计的。

## Android开发

[Tinker 源码分析之DexDiff / DexPatch](https://www.diycode.cc/news/2096)

tinker有个非常大的亮点就是自研发了一套dex diff、patch相关算法。本篇文章主要目的就是分析该算法。当然值得注意的是，分析的前提就是需要对dex文件的格式要有一定的认识，否则的话可能会一脸懵逼态。

[Android开发时，那些相见恨晚的工具或网站！](https://www.diycode.cc/news/2100)

一点工具整理分享。

[Android性能优化之GraphicsStatsService](https://www.diycode.cc/news/2099)

GraphicsStatsService是Android M(6.0)以后Google加入的用于收集汇总Android系统的渲染剖面数据(profile data)，主要途径是通过允许渲染线程请求匿名共享存储缓冲(ashmem buffer)来存放它们的统计信息来实现的。这篇文章旨在分析GraphicsStatsService的工作流程和这些统计信息的来龙去脉。

[深入了解 Android Nested Scrolling](https://www.diycode.cc/news/2101)

NestedScrolling弥补了原先事件分发机制的一个设计缺陷。

[Phonograph：一款 Material Designed 风格的音乐播放器](https://github.com/kabouzeid/Phonograph)

据说它已经拥有百万级别的下载量！

## 课外话题

[产品经理没做过成功产品，应该何去何从？](https://www.zhihu.com/question/56728746)

开发人员开发出成功产品，又该何去何从？

> 喜欢Diycode每日精选么？喜欢的话，不妨点个 **Star** 吧！

## 关注我们

| 社交账号  |  平台  | 关注人数 | 说明 |
| -------- | -------- | -------- | -------- |
| [Diycode每日精选](http://list.qq.com/cgi-bin/qf_invite?id=d469993d2c888e971c0fbb2309c4d84256968386b126b967)|   邮箱订阅  | 12000+ | 每日分享一次Android、iOS、Swfit技术干货  |
| [Code_News](https://github.com/DiyCodes/code_news) |    Github博客  |750+ | 每日邮件推送列表  |
| [优雅的程序员D](http://weibo.com/u/5891258264) |   微博  | 1500+ | 官方微博，每日分享开源信息  |
| [D_clock爱吃葱花](http://weibo.com/u/2480694892)  |   微博  | 1500+ | 日报发起人  |
|[YasicYu](http://weibo.com/3917305697/profile? rightmod=1&wvr=6&mod=personinfo&is_all=1)  |   微博  | 100+ | 日报发起人  |
|[安卓大王子](http://weibo.com/apkbus/)   |   微博  | 33000+ | 日报发起人  |

**微信公众号：**“优雅的程序员”，微信号：diycodes，目前关注人数 3000+ ；

![](http://upload-images.jianshu.io/upload_images/1846413-b42abfa70f909099.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**欢迎童鞋们把优质的技术文章链接分享到 http://www.diycode.cc/news ，让更多童鞋们看到它们！**
