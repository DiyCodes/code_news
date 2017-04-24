# 第215期：悦跑圈 Android 单业务开发，提高编译效率 15 倍

## 深度讨论

[悦跑圈 Android 单业务开发，提高编译效率 15 倍](https://www.diycode.cc/topics/761)

业务解耦手段有很多，本文提及的“provider解耦”仅仅是笔者习惯做法，对于文中描述需要解耦的地方，可以使用其他解耦方式。

一个工程多application并不是最好的开发方式，它不适合业务非常庞大的APP，例如支付宝、天猫、携程、链家等，超级APP必然是多project玩耍；也不适合业务量很少的APP，仅仅适合当前悦跑圈Android团队。

## Android开发

[有赞 App 模块化实战经验总结](https://www.diycode.cc/news/2383)

随着有赞电商业务的不断发展壮大，App 端所承担的功能也越来越重，特别是代码几易其主之后开始变得杂乱无章，牵一发而动全局的事情时常发生。为了应对团队壮大之后的开发模式，我们必须要对业务进行隔离，同时沉淀出通用组件，完善移动开发的基础设施。

[流利说团队：Building a Better Recorder in Android](https://www.diycode.cc/news/2384)

Recorder 可以说是流利说 app 中存在最长时间的类了, 用户通过这个类边录音边打分最后生成打分报告和对应的音频文件。本文分享了随着迭代的不断进行，流利说在 Recorder 使用上的心得。

[从卡顿到秒开：途牛Android端启动优化最佳实践](https://www.diycode.cc/news/2385)

本文主要介绍了途牛App启动流程的优化方案，从梳理现有启动流程、明确任务分级，合理调度、网络优化几个方面入手，解决App在低端机型上启动迟缓、卡顿的问题，达到了在大部分机型上秒开的效果，极大地提高了用户体验。

[移动端APM性能监控](https://www.diycode.cc/news/2386)

所谓『APM』，就是Application Performance Management的简称，我们利用这个系统来对应用的性能、可靠性进行线上的监控和预警的一种机制。现在App的开发技术相对成熟，而提升App的使用体验，就成了不同App之间的一个竞争点。

[MeiTuan：高仿美团客户端React-Native版，支持iOS、Android](https://github.com/huanxsd/MeiTuan)

![](https://github.com/huanxsd/MeiTuan/raw/master/screenshot/iOS_0.png)

支持: Android 4.1 (API 16)+ IOS(8.0+)。

## 课外话题

[一篇文章了解Google新开源的操作系统 Fuchsia](https://www.diycode.cc/news/2380)

Fuchsia是谷歌开发的一个操作系统，这是一个差不多从头研发的新系统。

> 喜欢Diycode每日精选么？喜欢的话，不妨点个 **Star** 吧！

## 关注我们

| 社交账号  |  平台  | 关注人数 | 说明 |
| -------- | -------- | -------- | -------- |
| [Diycode每日精选](http://list.qq.com/cgi-bin/qf_invite?id=d469993d2c888e971c0fbb2309c4d84256968386b126b967)|   邮箱订阅  | 12000+ | 每日分享一次Android、iOS、Swfit技术干货  |
| [Code_News](https://github.com/DiyCodes/code_news) |    Github博客  |750+ | 每日邮件推送列表  |
| [优雅的程序员D](http://weibo.com/u/5891258264) |   微博  | 1500+ | 官方微博，每日分享开源信息  |
| [D_clock爱吃葱花](http://weibo.com/u/2480694892)  |   微博  | 1500+ | 日报发起人  |
|[YasicYu](http://weibo.com/3917305697)  |   微博  | 100+ | 日报发起人  |
|[安卓大王子](http://weibo.com/apkbus/)   |   微博  | 33000+ | 日报发起人  |

**微信公众号：**“优雅的程序员”，微信号：diycodes，目前关注人数 3000+ ；

![](http://upload-images.jianshu.io/upload_images/1846413-b42abfa70f909099.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**欢迎童鞋们把优质的技术文章链接分享到 http://www.diycode.cc/news ，让更多童鞋们看到它们！**
