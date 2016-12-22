# 第142期：详谈 Android 高大上的图片加载框架 Glide

## 深度讨论

[你的 Android 发展路线是什么？](https://www.diycode.cc/topics/519)

大家一起来聊聊自己Android的发展路线，发展规划吧。是以后想管理层发展，还是继续走技术的道路？是继续Android还是打算弃坑？在当前的基础上，你的下一步深入，提升的发面是哪里？天南海北，大家随表聊聊吧。

## Android开发

[Android APK自我保护 - DEX/APK校验](https://segmentfault.com/a/1190000005105973)

DEX/APK 校验是在应用开发结束后，在本地计算出其 CRC 值或者 MD5值。在应用运行的时候，通过网络或者资源文件中获取事前算好的值进行比对，如果不一致则说明 DEX/APK 可能存在被篡改的风险。

[Android中热修复框架Robust原理解析并将框架代码从"闭源"变成"开源"](https://mp.weixin.qq.com/s/qCfVUU2H8eZjK287oCQi-A)

关于热修复技术点，其实虽然每家都有对应的框架，但是核心点都离不开动态加载机制。有了动态加载机制，然后就是具体修复方案问题了，对于Robust修复方案也是比较简单的。

[详谈 Android 高大上的图片加载框架 Glide](https://gold.xitu.io/post/585a091a1b69e6006cb79079)

我们可能已经能熟练的将Glide图片加载框架运用到我们的项目中，但是如果有人问你它是如何加载，工作原理是怎样的？为什么自定义GlideModule只需要在Manifest文件中加入meta-data即可？等等很多加载流程以及使用的注意事项。当然要想搞明白这些问题，就需要我们对Glide源码有个大致的认识，去剖析源码深处的奥秘。

[Weex Android SDK源码分析](http://www.jianshu.com/p/3160a0297345)

作者最近开始试水Weex开发，使用这么长一段时间，感觉写Weex还是非常方便的。作为一个Android开发，免不了要追查一下weex的sdk源码。

[Android使用Socket对大文件进行加密传输](http://www.jianshu.com/p/b2d9f84054d4)

作者在项目中使用Socket进行文件传输过程时，需要先进行加密。实现的过程中踏了一些坑，下面对实现过程进行一下总结。

[EmojiRain：小巧的 Android 掉 emoji 表情包实现开源控件](https://github.com/Luolc/EmojiRain)

![](https://raw.githubusercontent.com/Luolc/EmojiRain/master/ohters/dropping-demo.gif)

效果类似于微信中发送"生日快乐"和"么么哒"之类的词语时触发的动画效果。

## 课外话题

[为什么有的人工作多年还是老样子](http://www.jianshu.com/p/a5265c8e0ff8)

[程序员们也该知道的事——“期权和股票”](https://mp.weixin.qq.com/s/pfj9NLLuKYAfJJF84R9WAw)

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
