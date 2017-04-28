# 第219期：分析Android V2新签名打包机制

## 深度讨论

[分析Android V2新签名打包机制](https://www.diycode.cc/news/2418)

Android Studio 2.2发布之后公示了很多新特性，其中一些特性继承在了gradle plugin当中，这些不易被我们发现,比如新的签名机制(APK Signature Scheme v2)，本文对Android Gradle 2.2新推出来的新签名打包机制(V2新签名方案)作出相关分析，目前在Android 7.0以及之上版本已经对这套新签名机制提供了支持，因此随着版本的提升，新签名机制方案将是大势所趋。

## Android开发

[ApkChannelPackage：Android新一代多渠道打包神器](https://www.diycode.cc/news/2412)

ApkChannelPackage是一种快速多渠道打包工具，同时支持基于V1和V2签名进行渠道打包。插件本身会自动检测Apk使用的签名方法，并选择合适的多渠道打包方式，对使用者来说完全透明。

[Java技术之反射](https://www.diycode.cc/news/2413)

关于Java反射机制的文章很多，作者换了种方式来讲解反射的作用。

[Android ZXing（二维码）库全面使用解析](https://www.diycode.cc/news/2414)

不知不觉二维码已经深刻影响了我们的生活，为我们提供了极大的便利。线下付账、租一辆单车、或者去要一个妹子的微信号等等。张小龙把它称为从线下到线上的入口。正因为二维码如此的重要，并且出现的频率越来越高，所以 Android 应用中扫面二维码、条形码的需求也很常见了，本文就是来接入使用一个不错的二维码库 ZXing。

[Android共享元素转场动画兼容实践](https://www.diycode.cc/news/2415)

我们都希望我们的app有自己特殊的地方，转场动画就是一个比较好的方式让用户记住我们的应用。在Lollipop+ 上的版本实现起来十分的简单，但是如果想兼容低于5.0的版本，你或许需要检查Android系统的版本来做一些功能上的削减，或者你可以勇敢的手动来实现这个转换，疯狂的想法，但是我们可以来这么尝试一下。

## 课外话题

[如何评价斯坦福大学用 Javascript 取代 Java 作为计算机入门课程？](https://www.diycode.cc/news/2411)

斯坦福大学教授罗伯茨写了本很流行的Java教科书，并在2002年在斯坦福大学内推出了 Java 课 （CS 106A）作为计算机编程的入门课程。十五年之后，罗伯茨认为Javascript 已取代Java 在web 的地位，并推出新的计算机编程入门课（CS 106J）。斯坦福大学的网站说 课程CS 106J 覆盖的内容和 CS 106A大致相同，只不过是用JavaScript而不再是Java.

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
