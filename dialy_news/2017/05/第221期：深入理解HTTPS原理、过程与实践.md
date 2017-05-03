# 第221期：深入理解HTTPS原理、过程与实践

## 深度讨论

[深入理解HTTPS原理、过程与实践](https://zhuanlan.zhihu.com/p/26682342)

HTTP是不安全的，我们的页面也被运营商插入过小黄图广告（数据被篡改），对于HTTP来说，再简单不过，只需要设定相应的DNS，做一个中间人攻击，再将修改后的数据返回，这一方面可能泄露用户隐私数据，同时也对我们的品牌形象产生恶劣影响。

然而，当我们切换HTTPS时候，运营商的这些小九九就施展不开了，服务端认证不通过，浏览器不会展示相应的页面数据；运营商实施搞的这一套东东也就不能在用户不知情的情况下搞起来了，解决办法是去除相应的受污染的DNS。

全球最大的成人网站PornHub，YouPorn都要全面切HTTPS了,我们还在犹豫什么了？


## Android开发

[深入理解ServiceManager](https://www.diycode.cc/news/2429)

ServiceManager是安卓中一个重要的类，用于管理所有的系统服务，维护着系统服务和客户端的binder通信。

[Android下的WebView调试](https://www.diycode.cc/news/2430)

作者写写本篇文章的原因：由于现在的移动端项目集成h5越来越多，但是在排查问题的时候都是前端开发在浏览器中打开h5的地址，然后在调试h5页面的问题，这种调试能发现不少问题，但是效率很低，而且不是在嵌套在手机上显示，在手机端的适配问题很难发现，还有如果是涉及到要和native交互的数据这样也没办法测了。

[MVVM在Android上的正确使用方式](https://www.diycode.cc/news/2431)

Google发布DataBinding已经有一年时间了，网上也有很多教程。但是在笔者看过的大部分关于MVVM在Android上的实现的教程中，都存在一个十分之严重的问题，就是大部分的介绍MVVM的文章只不过是介绍DataBinding的文章。而在这些教程中，几乎都无一例外地把DataBinding生成的Binding类(或实体类当成是ViewModel层。这两种方法都有一个十分之大的漏洞，就是作为ViewModel层，几乎没有任何控制力。在这里，笔者介绍一个笔者总结出来的如何结合DataBinding在Android实现MVVM模式。

[otto源码解析及探索修改](https://www.diycode.cc/news/2432)

otto 是在 Android 系统上一个类似EventBus 的事件发布/订阅框架，相对于EventBus使用更简单，更精简。

[PaletteImageView：为你的图片添加阴影效果](https://github.com/DingMouRen/PaletteImageView)

![](https://github.com/DingMouRen/PaletteImageView/raw/master/imgs/img.gif)

## 课外话题

[性格不强势，关键时候总被牵着走怎么办？](https://www.zhihu.com/question/27160221)

怎么办呢？

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
