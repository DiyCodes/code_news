# 第76期：Android Hotfix 新方案——Amigo 源码解读

## 深度讨论

[1、Android Hotfix 新方案——Amigo 源码解读](http://www.diycode.cc/topics/280)

作者初衷：现在 hotfix 框架有很多，原理大同小异，基本上是基于qq空间这篇文章 或者微信的方案。可惜的是微信的 Tinker 以及 QZone 都没有将其具体实现开源出来，只是在文章中分析了现有各个 hotfix 框架的优缺点以及他们的实现方案。Amigo 原理与 Tinker 基本相同，但是在 Tinker 的基础上，进一步实现了 so 文件、资源文件、Activity、BroadcastReceiver 的修复，几乎可以号称全面修复，不愧 Amigo（朋友）这个称号，能在危急时刻送来全面的帮助。

[2、知乎上有哪些好的程序员可以关注？](https://www.zhihu.com/question/22576739/answer/120068239?from=profile_answer_card)




## Android开发

[自动检测性能问题 - BlockCanary 原理解析](http://www.woaitqs.cc/android/2016/09/01/check-performance.html)

从原理上分析 BlockCanary （已经更名叫 AndroidPerformanceMonitor ）是如何实现自动检测性能卡顿的。

[Freeline - Android平台上的秒级编译方案](https://yq.aliyun.com/articles/59122)

Freeline是蚂蚁金服旗下一站式理财平台蚂蚁聚宝团队在Android平台上的量身定做的一个基于动态替换的编译方案，稳定性方面：完善的基线对齐，进程级别异常隔离机制。性能方面：内部采用了类似Facebook的开源工具buck的多工程多任务并发思想, 并对代码及资源编译流程做了深入的性能优化。

[腾讯SNG质量部：Android 专项测试之GPU测试探索](http://mp.weixin.qq.com/s?__biz=MzAxMzYyNDkyNA==&mid=2651332483&idx=1&sn=ad50119ddc79aebe7de262f5b8978be1&scene=1&srcid=0901lPEVy0BynaJh29GPPBn3#wechat_redirect)

罗列了一些性能分析工具，教你如何做GPU测试。 

[Tiger：Google新作，号称最快速的Java依赖注入框架](https://github.com/google/tiger)

没错，就是最快速，不服去战。

[Android WebView·开车指南](https://jiandanxinli.github.io/2016-08-31.html)

超级好的一份 WebView 开车指南，力荐！

## 课外话题

[和程序猿谈恋爱是一种怎样的体验？](https://www.zhihu.com/question/27653728)

程序猿也有萌萌哒的时候。

[哪些 App 改变了你的坏习惯？](https://www.zhihu.com/question/21182063)

你呢？

**又到了令人愉快的周五，预祝童鞋们周末愉快，么么哒！**

> 喜欢Diycode每日精选么？喜欢的话，不妨点个 **Star** 吧！

## 关注我们

| 社交账号  |  平台  | 关注人数 | 说明 |
| -------- | -------- | -------- | -------- |
| [Diycode每日精选](http://list.qq.com/cgi-bin/qf_invite?id=d469993d2c888e971c0fbb2309c4d84256968386b126b967)|   邮箱订阅  | 12000+ | 每日分享一次Android、iOS、Swfit技术干货  |
| [Code_News](https://github.com/DiyCodes/code_news) |    Github博客  |309+ | 每日邮件推送列表  |
| [优雅的程序员D](http://weibo.com/u/5891258264) |   微博  | 600+ | 官方微博，每日分享开源信息  |
| [D_clock爱吃葱花](http://weibo.com/u/2480694892)  |   微博  | 1000+ | 日报发起人  |
|[YasicYu](http://weibo.com/3917305697/profile? rightmod=1&wvr=6&mod=personinfo&is_all=1)  |   微博  | 100+ | 日报发起人  |
|[安卓大王子](http://weibo.com/apkbus/)   |   微博  | 32141+ | 日报发起人  |



**微信公众号：**“优雅的程序员”，微信号：diycodes，目前关注人数 970 人；

![](http://upload-images.jianshu.io/upload_images/1846413-b42abfa70f909099.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**如果你是一个爱写技术博客的童鞋，欢迎发稿时在微博@上小编哦，优秀的文章能让更多童鞋们看到！小编：**[D_clock爱吃葱花](http://weibo.com/2480694892/profile?rightmod=1&wvr=6&mod=personinfo&is_all=1)
